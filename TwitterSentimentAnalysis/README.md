# TwitterSentiment

# CSV Generator
The CSVGenerate takes recent tweets on the given topic and generates a CSV with 2 columns, Tweet and Sentiment ('Positive/Negative').

Usage:

``` python3 CSVGenerate.py topic ```

# Get Colored Stats

getColoredStats.py gets the google trending topics of the day and then searches twitter for tweets on the topics. Then it creates an image consisting of circles for each topic, the larger the circle the more it was googled. And the color of the circle indicates the general opinion of twitter users in that topic. The more red the color the more negative tweets it has had, and green color means more postive tweets (it calculates average sentiment for each topic).

Dependencies:

tweepy
textblob
OpenCV
BeautifulSoup
Numpy

Usage:

``` python3 getColoredStats.py ```

Output (26th Jan 2018) :

![alt tag](https://github.com/atmc9/ML-personal/blob/master/TwitterSentimentAnalysis/trending26012018.png)
