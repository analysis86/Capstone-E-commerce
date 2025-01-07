# Capstone E-Commerce Sentiment Analysis Overview

 ## Problem Statement:
Amazon is an online shopping website that now caters to millions of people everywhere. Over 34,000 consumer reviews for Amazon brand products like Kindle, Fire TV Stick and more are provided. The dataset has attributes like  name of the product, product brand, categories, primary categories, reviews.date, reviews.text, reviews.title, and the sentiment. Sentiment is a categorical variable with three levels "Positive", "Negative“, and "Neutral". For a given unseen data, the sentiment needs to be predicted. We are required to predict Sentiment or Satisfaction of a purchase based on multiple features and reviews text.

## Project Structure
                      Week 1 & 2: Class Imbalance Problem        |         Week 3 & 4: Model Selection and Advanced Techniques 

## Week 1 & 2: Class Imbalance Problem
Data Preprocessing is done for the mentioned dataset. Drop missing values and duplicate values. Further, the dataset is tokenized and covert the text into lower case, remove pucntuations, remove special characters. The reviews.text column is cleaned and the data is then split into training, testing, and validation sets. Evaluation Metric is finalized and different settings are explored to build the sentiment model. Apart from the initial model that is trained and evaluated using the imbalanced data, two other models are built. One of the models is trained using class weights and the other model is trained using synthetically oversampled data. Finally, the results are compared for different models trained and evaluated under the best setting.
#• dew








