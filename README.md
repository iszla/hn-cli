# Hacker News cli - standalone

This is a version that combines [hn-cli](https://github.com/iszla/hn-cli) and [hn-parser](https://github.com/iszla/hn-parser), into one file. So no need to generate and load JSON files.

This version is built on, and requires, Python 3 and BeautifulSoup4

Based on [cortex](https://github.com/GGLucas/cortex)

# Install

Install BeautifulSoup4 using pip (use pip3 if you have both Python 2 and 3 on your machine)
```
sudo pip install beautifulsoup4
```
Clone this repo
```
git clone https://github.com/iszla/hn-cli-standalone
```
Run the app
```
./hn-cli
```

# Usage

* Press 'Enter' or 'o' to open the story in a browser
* Press 'c' to open the story on Hacker News to read the comments
* Set browser-command in the config file to use another browser, such as lynx
