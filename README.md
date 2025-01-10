#  Twitter_ Sentiment_Prediction_Analysis 



[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

![images](https://github.com/Gtshivanand/Twitter_Sentiment_Prediction_Analysis/blob/main/images/Twitter-sentiment-analysis-768x402.webp)

## Description:
This project focuses on analyzing and predicting sentiment from Twitter data using machine learning techniques. The primary goal is to classify tweets as positive or negative by leveraging natural language processing (NLP) and machine learning models. This analysis can provide valuable insights into public sentiment trends, helping businesses and organizations make data-driven decisions.

## Abstract: 
In today's digital era, social media platforms like Twitter serve as a powerful tool for gauging public sentiment. This project, Twitter Sentiment Prediction Analysis, aims to predict sentiment (positive or negative) from Twitter data using advanced machine learning techniques and natural language processing (NLP). By leveraging textual data from tweets, the project focuses on preprocessing raw data, extracting meaningful features, and applying machine learning algorithms to classify sentiments accurately.

The analysis begins with extensive preprocessing, including tokenization, stopword removal, stemming, and feature engineering using techniques like TF-IDF and word embeddings. Various supervised learning models, such as Logistic Regression, Support Vector Machines (SVM), and Random Forest, are trained and evaluated to identify the most effective approach for sentiment classification.

The project not only highlights sentiment trends over time but also provides actionable insights for businesses, enabling them to optimize their strategies based on public opinion. Additionally, it demonstrates the practical application of NLP and machine learning in addressing real-world challenges. By accurately predicting sentiment, this work aims to enhance decision-making processes, improve customer engagement, and reduce costs associated with sentiment analysis.

## Objective:
To provide actionable insights into public sentiment and support cost-saving strategies through accurate sentiment prediction.

## Problem Statement

The ability to analyze user sentiment through tweets and comments can provide significant value to companies during __product launches__. By understanding customer behavior and incorporating __sentiment analysis__, companies can gain insights from user feedback. This empowers them to make informed decisions, take necessary actions, and improve overall __revenue__ by addressing customer concerns and making targeted improvements accordingly.

![images](https://cdn.analyticsvidhya.com/wp-content/uploads/2021/06/79592twitter.jpg)

## Machine Learning and Data Science

Our approach involves utilizing machine learning techniques and text extraction to predict the sentiment of a given text, determining whether it is positive or negative. Initially, we will analyze the text and examine the various words present within it. Once we have a comprehensive understanding of the text, we will proceed with the machine learning analysis, employing deep neural networks. The output from this analysis will be utilized in subsequent machine learning operations to generate predictions regarding the sentiment of the text, specifically determining whether it is positive or negative.

## Natural Language Processing (NLP)
We would be using the __natural language processing__ that is required when doing the machine learning analysis. Performing the natural language processing ensures that the words that are present are converted into mathematical vectors that are used for different machine learning models for prediction. Once the mathematical vectors are converted into different vectors, they are given for the machine learning models for prediction respectively. Therefore, with the features that are present in the text along with some newly created features, the machine learning, and deep learning models would be using those techniques and ensures that they are getting the best outputs respectively. 

## Vectorizers 

It is important to use vectorizers that are important for machine learning. Therefore, a given text which is in the form of a string is converted into a vectorial representation which is what is being used by machine learning models for prediction. Below are some of the vectorizers that were used in the process of converting a text into a mathematical representation. 

* [__Count Vectorizer__](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html)
* [__Tfidf Vectorizer__](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)

## Machine Learning Models

In this project, there was only one ML model used to get the prediction of the sentiment of tweets. Below is the model that was used for the task of prediction.

* [__Deep Neural Networks__](https://www.tensorflow.org/api_docs/python/tf/keras/Model)

## Exploratory Data Analysis (EDA)

After performing __exploratory data analysis__, it could be seen based on the results that there is a comparatively more number of neutral sentences compared to either positive or negative sentiments. With the use of __word clouds__, it could be seen that words such as good, awesome, and great were used most frequently. On the contrary, it could be seen for the negative __word cloud__ that words such as hate, sorry and sad were used most frequently. 

We have an image depicting a dataframe and a list of features. We will utilize the 'text' feature as input and consider the 'sentiment' feature as our target variable. Our goal is to predict the likelihood of a text being categorized as positive, negative, or neutral.

<img src = "https://github.com/Gtshivanand/Twitter_Sentiment_Prediction_Analysis/blob/main/images/Sentiment%20countplot.jpg "/>

The countplot below illustrates that the majority of texts are classified as neutral sentiment, while the count of negative and positive texts is comparatively lower. This indicates a higher prevalence of neutral sentiments in the dataset.

<img src = "https://github.com/suhasmaddali/Twitter-Sentiment-Analysis/blob/main/images/Sentiment%20countplot.jpg"/>

Wordcloud gives a good representation by the presence of words based on their size. In other words, more frequent words appear in higher size as compared to others. Words such as "thank" and "day" are used most often in the positive tweets. 

<img src = "https://github.com/Gtshivanand/Twitter_Sentiment_Prediction_Analysis/blob/main/images/Positive%20wordcloud.jpg"/>

The wordcloud provided showcases negative tweets within the dataset. Notably, recurring words like "hate" and "sad" are prevalent, indicating their significance in identifying negative sentiment.

<img src = "https://github.com/Gtshivanand/Twitter_Sentiment_Prediction_Analysis/blob/main/images/Negative%20wordcloud.jpg"/>

## Key Features:


* Preprocessing of raw Twitter data (tokenization, stemming, stopword removal).

* Exploratory Data Analysis (EDA) to understand sentiment patterns.

* Feature engineering with techniques like TF-IDF and word embeddings.

* Implementation of machine learning algorithms (e.g., Random Forest, SVM, Logistic Regression).

* Evaluation of model performance with metrics like accuracy, precision, recall, and F1-score.

* Visualization of sentiment trends and model outcomes.

## Hyperparameter Tuning 

In our project, after gaining a comprehensive understanding of various machine learning models, we will proceed with hyperparameter tuning. This crucial step aims to select optimal hyperparameters that can yield the best results for each specific model. By carefully selecting these hyperparameters, we can enhance the accuracy and performance of our machine learning models. Our objective is to explore and grasp the influence of different hyperparameters on the models and how they impact the outcomes for various problem statements. Ultimately, we aim to apply these optimized machine learning models in a production environment, leveraging their capabilities to achieve the desired results.

## Results 

The observed discrepancy between the training loss and the test loss suggests the presence of overfitting in the data. Despite this, the model could still be utilized for predictions, considering its potential ability to generalize well on unseen test data, despite its exceptionally strong performance on the training data.

<img src = "https://github.com/Gtshivanand/Twitter_Sentiment_Prediction_Analysis/blob/main/images/Model%20Performance.jpg"/>

## # Feedback and Suggestions:

I’d love to hear your thoughts, feedback, and suggestions! Feel free to connect with me:

 *LinkedIn*: [Shivanand Nashi](https://www.linkedin.com/in/shivanand-s-nashi-79579821a)
 
 *Email*: shivanandnashi97@gmail.com


Looking forward to connecting and exchanging ideas!




