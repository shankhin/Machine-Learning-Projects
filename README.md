This repository contains all my personal machine learning projects done both as part of my schooling for my graduate level **Intro to Machine Learning Course**.
# Project 1 - Logistic Regression
In this project we investigated the performance of linear classification models on two benchmark datasets, a normalised datset of possible health markers for diabetes and another normalised dataset of possible markers for a good red wine and were then tasked with classification of said data points into whether the person has diabetes and whether the red wine is good or bad. I achieved this using two alogorithms - a simple Logistic Regression model and another Logistic Regression model with an added bias and then feature selection was done to further increase the accuracy until I got my highest cross-validation accuracy of **∼70%** accuracy.
# Project 2 - Text classsification using Sentiment Analysis 
In this project we investigated the performance of different classification algorithms on posts posted in 5 different subreddits - from the public domain www.reddit.com. Namely, the 5 subreddits were - Instagram, Facebook, Viber, LinkedIn, Telegram and the algorithm were a Naive Bayes algorithm written from scratch and a Random Forest Classification algorithm from the SciKit Learn library applied on the dataset. There were several preprocessing steps taken in order to clean the data and have the data be as clean as possible from undesirable noise data so as to not hinder our prediction process and make it as accurate and precise as possible. I observed that the Naive Bayes classifier performed much worse (test accuracy of **60-70 %**) than the Random Forest Classifier (test accuracy of **85-95 %**). Additionally, I observed that fine tuning parameters like max features, stop words, strip accents in the Count Vectorizer class greatly affected test accuracies, especially in the Naive Bayes classifier.
# Project 3 - Image classsification using Convolutional Neural Networks 
This assignment focused on this use of machine learning to interpret image data. For this assignment each group was tasked with classifying a images from a given dataset into 10 classes. This was performed using a Convolutional Neural Network (CNN). The parameters for this CNN were then fine tuned in order to produce a final model with **∼84%** accuracy.
