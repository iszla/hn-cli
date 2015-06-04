# Hacker News cli - standalone


hn-cli is built on Python and BeautifulSoup4

# News

I have added a Python 2 version, this version does not have any external config options.

Based on [cortex](https://github.com/GGLucas/cortex)

# Install

Install BeautifulSoup4 using pip (use pip3 if you have both Python 2 and 3 on your machine)
```
sudo pip install beautifulsoup4
```
Clone the repo
```
git clone https://github.com/iszla/hn-cli
```
Run the app
```
./hn-cli/hn-cli
```

# Usage

* Press 'Enter' or 'o' to open the story in a browser
* Press 'c' to open the story on Hacker News to read the comments
* Press 't' to toggle between Top and New stories
* Set browser-command in the config file to use another browser, such as lynx (currently not available in the python2 verison)
