
<h1 align="center">
  <b>Twitter Tweet Analysis<br></b>
</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Library-Flask-red.svg?style=flat-square">
  <img src="https://img.shields.io/badge/Tool-ApacheSpark-yellow.svg?style=flat-square">
  <img src="https://img.shields.io/badge/Language-Python-purple.svg?style=flat-square">
</p>

## Data Analytics Assignment-3
This is my college assignment for the course on Data Analytics.

### Objective of the project:
To create a program using Apache Spark an online streaming Real-Time Analytics Platform to process the tweets and identifying the trending hashtags from Twitter and, finally, retrieve top hashtags and representing the data in a real-time dashboard.

### Datasetused in this porject
The dataset used for this project is Twitter tweets. In, order to get the Twitter tweets we need Twitter API, for that first, we need to register for the Twitter Developer account. After the registration click on the create an application and, finally, generate the access token for the project.<br>
The access tokens will lool something like this:
|       ENV         | Credentials                                             |
|-------------------|---------------------------------------------------------|
|**ACCESS_TOKEN**   | 100828113-6s4LYeoYFtXZCDg6dgojawMPPWIoptYIYFQdfdYXu     |
|**ACCESS_SECRET**  | ULcfr3haQTgJ5VhBE6oxdfdfutkjfddfffh9kWVy7lyKtKqh37Fg0   |
|**CONSUMER_KEY**   | jlY6vQyHYgbDdfdfdtKBOvpV9gK2Uj                          |
|**CONSUMER_SECRET**| pBAAqvoQxijOlCwdfddfzdfwefpnhV4CMd48uTjmTVdoodzK        |

### Methodology used in developing project:
<img src="/asset/methodology.png"/>

- First, the tweets from Twitter has received to the machine using the Twitter API.
- A python program has implemented to receive the data and then sent through a TCP Socket.
- The data been processed with the pyspark using Apache spark and then the Twitter tweets and trending hashtag would be outputted.
- To display the data using flask micro web app to display the data in a visual representation.

### Running the Application
Lets run the application in the order:

```
1. twitter_app.py
```
 
```
2. spark_app.py
```

```
3. app.py(Flask Application)
``` 

### Visual representation
You can access the real-time data in visual representation by accessing this URL given below.

```
<http://localhost:5001/ > or <http://127.0.0.1/5001>
```

### Final Output
The **output of this project** is recorded and uploaded in YouTube
- YouTube Link[Output]: **https://youtu.be/O8vH669EOAk**

<br><br><br>
<h4 align="center">
  This assignment is fully caffeinated ☕ by <a href="https://github.com/guruhariharaun">Guru HariHaraun</a>
</h4>
<br><br><br><br>
<img src="/asset/footer.png"/>
