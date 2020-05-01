# InstagramAutomation
Automation of an instagram account using "Instagram Private API" module

# Functions
All the available functions on [Instagram API](https://instagram-private-api.readthedocs.io/en/latest/api.html)

This code, we can:

- List all the followers and following users (from any IG account);
- Get mutual friends, following alone and follower alone (see [code description](https://github.com/luiseduardobr1/InstagramAutomation/blob/master/InstagramAPI.ipynb) for more)
- Extract general information about the photos, like date of publication, location, latitude, longitude,
number of likes, comments and the direct link for the publication;
- Download all photos from an account;
- Get the users who most liked the photos or commented the most (on any user account);
- Like all photos of an user;
- How to be the first comment on every famous instagram page;
- And Many more...

# Usage
1) Install the libraries:
* [Instagram Private API](https://github.com/ping/instagram_private_api)
* [Instagram Private API Extensions](https://github.com/ping/instagram_private_api_extensions)

May be necessary for some functions:
* [Pandas](https://pandas.pydata.org/)
* [Requests](https://requests.readthedocs.io/pt_BR/latest/user/quickstart.html)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Covid](https://pypi.org/project/covid/)

2) Put your instagram's username and password on the code:
```Python
user_name = 'YOUR USERNAME'
password = 'YOUR PASSWORD'
```

3) Run the Jupyter Notebook cells in order and have fun! **Be careful, instagram can block or ban your account if you use it as spam**

