# Predicting-the-video-game-hype-train-Playing-around-with-Naive-Bayesian-Learning

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A Brief Introduction
=======================

tl;dr

Using a Naïve Bayesian classifier and a dataset of 1515 video game ratings, I am predicting which developer is most likely to make a game with specific properties (metascore, ESRB rating, genre, platform) in the future.

Naïve Bayesian learning
==========================
A Naïve Bayes classifier is a very simple method to predict categorial outcomes. A well-known application is text classification, especially predicting whether a text is spam. Here, the classifier tries to use the information about the occurrence of certain words in telling us whether an e-mail message is spam or not. If I understand the method correctly, it’s called “naïve” because it makes some oversimplified assumptions about the data it’s classifying, especially that all events (or values of a certain feature) are independent from each other (i.e. from the values of other features). So it’s neglecting all possible correlations between the different features. That makes the method very fast, even when there are many features used for prediction.

Of course, the method can be applied to other data than e-mails. So, I wanted to try it with the videogames dataset I’ve investigated before. The dataset is available from Kaggle. I still have to gain some experience with the methodology. 


DataSet : https://www.kaggle.com/skateddu/metacritic-games-stats-20112019
