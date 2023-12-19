# Fake News Detection using Machine Learning

## Introduction

Embarking on the journey of detecting fake news through machine learning, this project utilized a dataset from Kaggle containing 20,800 entries. The primary goal was to build a classifier capable of distinguishing between real and fake news articles, denoted as 0 and 1, respectively. The initial steps involved loading the dataset, addressing duplicates, and handling missing values, resulting in a refined dataset of 18,285 rows.

## Text Processing

The crux of the project lies in effective text processing. The 'combined' column, formed by merging 'author' and 'title,' underwent meticulous cleaning. This process included removing punctuation and stopwords, ensuring that the text was prepared for subsequent analysis. The transformation into a matrix of token counts using Scikit-learn's CountVectorizer paved the way for the machine learning model

## Data Splitting

To train and assess the model's performance, the dataset was split into an 80% training set and a 20% testing set. This division allowed for the evaluation of the classifier's ability to generalize to unseen data, a crucial aspect of any machine learning project.

## Multinomial Naive Bayes Classifier

Choosing the Multinomial Naive Bayes classifier, renowned for its efficacy in text-based classification, marked a pivotal decision. The model was trained on the designated training set to learn the patterns in the token count matrix.

## Model Evaluation

A thorough evaluation of the model's accuracy ensued, employing metrics such as precision, recall, and F1-score. The classification report provided a comprehensive overview of the classifier's effectiveness in distinguishing real from fake news articles.

## Results and Conclusion

The Multinomial Naive Bayes classifier showcased an impressive accuracy of approximately 94% on the test dataset, underlining its robustness in generalizing to previously unseen data. This project not only delves into the technical intricacies of machine learning but also highlights its tangible application in combating issues such as the proliferation of fake news.
