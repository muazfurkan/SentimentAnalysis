# Sentiment Analysis for Tweet Sentences using Word2Vec and RandomForests Model

This project aims to perform sentiment analysis on tweet sentences using a dataset and the Word2Vec model.

## Dataset
The project utilizes a dataset containing tweet sentences for sentiment analysis. The dataset includes not only the tweet sentences but also the associated sentiment labels for each sentence.

You can find the used dataset at the following link: https://www.kaggle.com/datasets/dunyajasim/twitter-dataset-for-sentiment-analysis

## Word2Vec Model
In this project, the Word2Vec model, which is a word vector model, is employed for sentiment analysis on tweet sentences. Word2Vec utilizes word vectors to represent word similarities and relationships.

## Random Forests Model
In this project, a Random Forest model is used for sentiment analysis on tweet sentences, utilizing vectors obtained from the data. The Random Forest model is trained using the vectors derived from the tweet sentences. The trained model makes sentiment predictions for the provided sample sentences.

## Project Workflow
The dataset should be provided as a CSV file, including the tweet sentences and their corresponding sentiment labels.
The dataset undergoes preprocessing steps using the Word2Vec model to transform the input data into numerical vectors.
A machine learning model is trained for sentiment analysis using a separated dataset of training and testing data.
The trained model can be utilized to predict the sentiment of new tweet sentences.

## Requirements
This project has been developed using the Python programming language. To use this project, you need to install the following libraries:

- numpy
- pandas
- scikit-learn
- word2vec

## Contributing
We welcome contributions of any kind! If you would like to contribute to this project, please open an issue or submit a pull request on the GitHub repository.