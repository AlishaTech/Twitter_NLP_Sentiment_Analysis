# Twitter_NLP_Sentiment_Analysis
This Twitter_NLP_Sentiment_Analysis is about classifying positive tweets from negative tweets with machine learning models for text mining, classification, text analysis, data visualization, and data analysis.

# Introduction

We will explore sentiment analysis, an application of Natural Language Processing (NLP). From opinion polls to creating entire marketing strategies, this domain has completely reshaped the way businesses work.

Thousands of text documents can be processed for sentiment (and other features including named entities, themes, topics, etc.) in seconds, compared to the hours it would take a team of people to manually complete the same task. 

I started with preprocessing and cleaning the raw text of the tweets. Then I looked throught the text to get some intuition about the context of the tweets. Then I extract numerical features from the data and use these feature sets to train models and identify sentiments of the tweets.

I’m excited for you to join me on this NLP challenge.

# The Problem Statement:

The objective of this task is to detect hate speech in tweets. For example, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label ‘1’ denotes the tweet is racist/sexist and label ‘0’ denotes the tweet is not racist/sexist, the objective is to predict the labels on the given test dataset.

Note: The F1-Score is the evaluation metric. 

# Cleaning the Tweets

I've cleaned the text data so it's arranged in a structured format. 

It has been preprocessed before mining and then machine learning algorithms are applied. 

Later I extracted numeric features from my Twitter text data using the unique words for the feature space. I preprocessed my data in order to get better quality feature space.

# Data Storytelling and Visualization from Tweets

In this section, we will explore the cleaned tweets text. Exploring and visualizing data, no matter whether its text or any other data, is an essential step in gaining insights.

Before I begin, I ask myself these questions:

What are the most common words in the entire dataset?
What are the most common words in the dataset for positive and negative tweets?
How many hashtags are in a tweet?
Which trends are associated with my dataset?
Which trends are associated with either of the sentiments? Are they compatible with the sentiments?

# Conclusion

Throughout my analysis, I learned how to approach a sentiment analysis problem. I started with preprocessing and exploration of data. Then I extracted features from the cleaned text using Bag-of-Words and TF-IDF. Lastly, built models using both of the feature sets to classify the tweets.

