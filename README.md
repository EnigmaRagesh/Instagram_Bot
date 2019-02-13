# Instabot

## Requirements

 - Linux
 - Google Chrome
 - Selenium library
 ### Install ChromeDriver
 

```
sudo apt-get install unzip
```
```

wget -N http://chromedriver.storage.googleapis.com/2.26/chromedriver_linux64.zip
unzip chromedriver_linux64.zip
chmod +x chromedriver
``` 
```
sudo mv -f chromedriver /usr/local/share/chromedriver
sudo ln -s /usr/local/share/chromedriver /usr/local/bin/chromedriver
sudo ln -s /usr/local/share/chromedriver /usr/bin/chromedriver
```
    
### Install dependencies and Selenium:
```
sudo apt-get install python-pip
```
```
python -m pip install selenium
```

## InstaBot

> Add your hashtag preferences in the code
> Add your instagram username and password
### Run Bot

    python InstaBot.py
