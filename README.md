# Coronavirus-Tweet-Sentiment-Analysis

Predictive model for Covid-19 tweet sentiment analysis based on the tweet dataset from January 4, 2020 to December 4, 2020.

-----------------------------------------------------

💾 Table of Content
Introduction

Problem Statement

Objectives

Data Summary

Steps involved

Exploratory Data Analysis

Feature Engineering

Algorithms used

Model Evaluation

Conclusion
-----------------------------------------------------

📄 Introduction
Sentiment Analysis is the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer’s attitude towards a particular topic is Positive, Negative, or Neutral.

Tweets are often useful in generating a vast amount of sentiment data upon analysis. These data are useful in understanding the opinion of the people about a variety of topics.

-----------------------------------------------------

❓ Problem Statement
We are provided with a coronavirus tweets csv file which contains more than 40000 tweets from people around the world on covid 19 and our aim is to analyze these tweets and predict the sentiment of each of the tweet by classifying them into three categories positive, negative and neutral.

-----------------------------------------------------

🎯 Objectives:
Analyze the tweets regarding COVID 19 and get insights regarding people’s sentiment.

To build a classification model to predict the sentiment of COVID-19 tweets which have been pulled from Twitter.

-----------------------------------------------------

📖 Data Summary
The dataset contained “Tweets” gathered during pandemic times. The shape of the dataset is (41157, 6). The target variable is ‘Sentiment’.

● Username : The username of the person on twitter

● Screenname : The screenname of the person on twitter

● Location : The location from where the tweet was tweeted

● TweetAt : The date of the tweet

● OriginalTweet : The tweet itself unfiltered

● Sentiment : The sentiment of the tweet our target variable

# Coronavirus-Tweet-Sentiment-Analysis

Predictive model for Covid-19 tweet sentiment analysis based on the tweet dataset from January 4, 2020 to December 4, 2020.

-----------------------------------------------------

⚙️ Steps Involved

Analyzing dataset

Exploratory Data Analysis

Text Preprocessing

Feature Engineering

Classification
> Model Training 
> Result from model training
> 
Observations & Conclusion

-----------------------------------------------------

💻 Algorithms used

•Logistic Regression

•Passive Aggressive Classifier

•Stochastic Gradient Descent Classifier

•Support Vector machine

•Random Forest

-----------------------------------------------------

CONCLUSION 

Thus we conclude our project on coronavirus Tweet Sentiment Analysis. We used 5 different classification algorithms as Logistic regression, SVM, SGD, Random forest & passive aggressive classifier. We started by analyzing the dataset to learn more about the variables involved.

As a part of Exploratory Data Analysis, we tried to derive different patterns in the data. For building different classification models we used the future 'OriginalTweet' and the target variable 'Sentiment'. By performing tweet cleaning, Removing stopwords, Removing punctuations and Stemming, We prepared the column 'OriginalTweet' for modelling. We applied 5 different classification models among which Logistic Regression is the best performing model. Logistic Regression with 80% (approx) accuracy performed well for multinomial classification.

We hope this project will be helpful for the government and NGO’S to take adequate measures in policy making and rehabilitation respectively . 

Various project organizations can make profit through the production and distribution of essentials items during the pandemic by analyzing various sentiments.
