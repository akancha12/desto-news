# DestoNews


A django application that provides a sentiment balanced, location-based non-repetitive dynamic news-feed using NLP techniques on data extracted from Twitter.

### Overview

The measure of news data an individual can routinely get to nowadays would have been unimaginable a hundred years back. Yet, despite everything we have only 24 hours in a day, and just a single pair of eyes to read, and so the question arises: how to get as much valuable news as possible in a limited time?  

A “news feed service” is designed to effectively deliver the most relevant and valuable news content to individual readers. In order to recognize such a service, the system needs to analyze and evaluate a user’s preferences and all recent news content, which requires processing a huge amount of data. Fortunately, meeting high data processing demands is something natural language processing technology is good at.  Natural language processing technology can assist news media platforms in building highquality and accurate news information to enhance their content value. The technology can also analyze a particular news to help readers to separate repeated news bits from the sea of information.  The idea here is to create a fair, sentiment balanced, non-repetitive, and appropriate news-feed that can provide news for any stated location by utilizing the Twitter API. And  If the topic is not in the language of the user's preference, the translated version is presented along with the original text. 

Major modules include UI interface development and Backend development. 

UI is made using HTML, CSS and JavaScript. The sub-modules include Authentication (handled by accounts), templates etc. 

Backend module is developed using a python frameowrk known as Django. It further includes sub-modules like Tweepy authentication, Tweets extraction, Tweets Processing, Sentiment Analysis, Translator, etc. 

The main file for tweet extraction and processing is news/views.py .

### SetUp

In order to run this project on your machine, follow the following steps:

+ Install a virtual environment wrapper, if you don't have one.

  ```commandline
  pip install virtualenvwrapper-win
  ```
  (Windows)
  ```commandline
  pip install virtualenv
  ```
  (Mac)


+ Make a virtual environment
  ```commandline
  mkvirtualenv destoNews
  ```
  (Windows)
  ```commandline
  virtualenv destoNews
  source destoNews/bin/activate
  ```
  (Mac)


+ Install Django
  ```commandline
  pip install django
  ```
+ You can check the version of django using the following command,
  ```
  django-admin --version
  ```
+ You can install other api and libraries required to run this project, using the command like the ones listed below.
  ```
  pip install tweepy
  pip install textblob
  pip install <name_of_the_library>
  ```
  
[Click here](https://youtu.be/VlEOutfMIdU) to watch the video demo of the project which explains the whole code and working demo of the project.
