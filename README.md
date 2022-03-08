# YouTube_Trending-Machine_Learning-
Compared Random Forest model against the deep learning model (LSTM) in classifying YouTube video ratings
## Problem Definition and Context
YouTube (the world-famous video sharing website) maintains a list of the top trending videos on the platform. To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes).

This dataset includes several months (and counting) of data on daily trending YouTube videos. Data is included for the US, CA, and GB regions, with up to 200 listed trending videos per day.

Each region’s data is in a separate file. Data includes the video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count.
### What analysis is to be performed?
First, join the 3 datasets and create an extra column of Country to distinguish the data. Random Forest can then be used to create the classification model. Choose 80% Data randomly from dataset to train the model. Use rest to test and validate the model and test the accuracy. Remove the columns which are not useful for prediction. Use of Random Forest to classify the model Proper Training, testing and Validation
### RNN-LSTM-KERAS-NLTK
Create a model using RNN-LSTM-KERAS + NLTK to form a Deep Learning model. Only category ids (as output) and Description (as input text) is to be taken for this model. Find the Validation Accuracy after dividing the dataset into 80% training and 20% test set. Use 30% dropout to COMBAT OVERFITTING.

