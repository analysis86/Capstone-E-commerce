# Capstone E-Commerce Sentiment Analysis Overview

 ## Problem Statement:
Amazon is an online shopping website that now caters to millions of people everywhere. Over 34,000 consumer reviews for Amazon brand products like Kindle, Fire TV Stick and more are provided. The dataset has attributes like  name of the product, product brand, categories, primary categories, reviews.date, reviews.text, reviews.title, and the sentiment. Sentiment is a categorical variable with three levels "Positive", "Negative“, and "Neutral". For a given unseen data, the sentiment needs to be predicted. We are required to predict Sentiment or Satisfaction of a purchase based on multiple features and reviews text.

## Project Structure
• Jupyter notebook: Contains Jupyter notebook with Data Preprocessing Part and the Sentiment Notebook.

                      Week 1 & 2: Class Imbalance Problem        |         Week 3 & 4: Model Selection and Advanced Techniques 

## Week 1 & 2: Class Imbalance Problem
Data Preprocessing is done for the mentioned dataset. Drop missing values and duplicate values. Further, the dataset is tokenized and covert the text into lower case, remove pucntuations, remove special characters. The reviews.text column is cleaned and the data is then split into training, testing, and validation sets. Evaluation Metric is finalized and different settings are explored to build the sentiment model. Apart from the initial model that is trained and evaluated using the imbalanced data, two other models are built. One of the models is trained using class weights and the other model is trained using synthetically oversampled data. Finally, the results are compared for different models trained and evaluated under the best setting.

• Perform an EDA on the dataset.

• See what a positive, negative, and neutral review looks like

• Check the class count for each class. It’s a class imbalance problem.

• Convert the reviews in Tf-Idf score.

• Run multinomial Naive Bayes classifier. Everything will be classified as positive because of the class imbalance.

### Tackling Class Imbalance Problem:

Oversampling or undersampling can be used to tackle the class imbalance problem. In case of class imbalance criteria, use the following metrices for evaluating model performance: precision, recall, F1-score, AUC-ROC curve. Use F1-Score as the evaluation criteria for this project. Use Tree-based classifiers like Random Forest and XGBoost. Note: Tree-based classifiers work on two ideologies namely, Bagging or Boosting and have fine-tuning parameter which takes care of the imbalanced class.

## Week 3 & 4: Model Selection and Advanced Techniques 
### Model Selection:

Apply multi-class SVM’s and neural nets. Use possible ensemble techniques like: XGboost + oversampled_multinomial_NB. Assign a score to the sentence sentiment (engineer a feature called sentiment score). Use this engineered feature in the model and check for improvements. Draw insights on the same.

### Applying LSTM:

Use LSTM for the previous problem (use parameters of LSTM like top-word, embedding-length, Dropout, epochs, number of layers, etc.)

  • Compare the accuracy of neural nets with traditional ML based algorithms.

  • Find the best setting of LSTM (Neural Net) and SVM's that can best classify the reviews as positive, negative, and neutral.

  • Hint: Use techniques like Grid Search, Cross-Validation and Random Search

### Topic Modeling:

• Cluster similar reviews. Note: Some reviews may talk about the device as a gift-option. Other reviews may be about product looks and some may highlight about its battery and performance. Try naming the clusters.

• Perform Topic Modeling Hint: Use scikit-learn provided Latent Dirchlette Allocation (LDA) and Non-Negative Matrix Factorization (NMF).









