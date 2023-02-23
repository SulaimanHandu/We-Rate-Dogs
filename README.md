# We-Rate-Dogs
This is an analysis showing the extraction of data from twitter's API, Assessing, Cleaning and performing exploratory analysis. The Data was extracted from Tweets shared on the Twitter handle WeRateDogs. 

# Libraries Required 
* import pandas as pd 
* import numpy as np
* import matplotlib.pyplot as plt
* import seaborn as sns
* import requests
* import tweepy
* import json
* from PIL import Image
* from io import BytesIO
* from wordcloud import WordCloud, STOPWORDS, ImageColorGenerator
* from tweepy import OAuthHandler
* from timeit import default_timer as timer
#  Data Wrangling
## Gathering Data
1. Importation of manually downloaded csv file
2. programatic download of  tsv file form Udacity website 
3. Extracting data from Twitter's API using Tweepy 

## Assessing Data 
This is done manually and programatically 
1. Identifying Quality Issues 
2. Identifying Tidiness Issue

## Clean Data 
Data has to be ready for analysis. all quality and tidiness issues are rectified to make data completely read for analyses. 

# Analyses and Insight
1. The most popular dog names
2. What stages do we have most dogs
3. Ratings were mostly used to classify our dogs
4. Corrrelation between retweet_count and favourite_count
5. Most Favourite dogs
6. What are the most used words in our tweets

# Reference
>[To creating a word cloud, Checkout DataCamp](https://www.datacamp.com/tutorial/wordcloud-python)
