BBC news classifier

Overview

This repository contains code and documentation for a text classification project aimed at categorizing news articles into different topics. The project involves data cleaning, preprocessing, text representation, topic clustering, manual labeling, and building a classification model.

Introduction

The goal of this project is to automatically categorize news articles into specific topics using machine learning techniques. The process involves several steps, from data cleaning and preprocessing to building and evaluating a classification model.

Data Cleaning and Preprocessing

- Remove irrelevant information like HTML tags, advertisements, and non-text content.
-Tokenize the text and remove stop words.
-Perform lemmatization or stemming to reduce words to their base form.
-Handle missing data and ensure a consistent format.

Text Representation
Convert the text data into a numerical format suitable for machine learning models.
Techniques include TF-IDF (Term Frequency-Inverse Document Frequency) or word embeddings (e.g., Word2Vec, GloVe).

Topic Clustering

Apply clustering algorithms (e.g., K-means, hierarchical clustering) on preprocessed text data to group similar articles.

Topic Labeling

Manually inspect a sample of articles in each cluster to assign meaningful topic labels.
This step aids in labeling clusters with relevant topics.

Classification Model
-Split the data into training and testing sets.
-Train a supervised machine-learning model (DecisionTreeClassifier, SGDClassifier, MLPClassifier, Naive Bayes, SVC, Decision Tree)

Evaluation results for Model using Word to Vec 

Naive Bayes :
Accuracy: 0.921 	Precision: 0.921 	Recall: 0.921 	F1-Score: 0.920

SVC :
Accuracy: 0.939 	Precision: 0.938 	Recall: 0.938 	F1-Score: 0.937

Decision Tree :
Accuracy: 0.910 	Precision: 0.910 	Recall: 0.907 	F1-Score: 0.908

SGD Classifier :
Accuracy: 0.944 	Precision: 0.943 	Recall: 0.944 	F1-Score: 0.942


Evaluation results for Model using  TfidfVectorizer

Naive Bayes :
Accuracy: 0.971 	Precision: 0.969 	Recall: 0.970 	F1-Score: 0.969

SVC :
Accuracy: 0.989 	Precision: 0.989 	Recall: 0.989 	F1-Score: 0.989

Decision Tree :
Accuracy: 0.827 	Precision: 0.825 	Recall: 0.827 	F1-Score: 0.824

SGD Classifier :
Accuracy: 0.989 	Precision: 0.989 	Recall: 0.989 	F1-Score: 0.989
