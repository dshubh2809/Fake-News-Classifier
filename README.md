# Fake-News-Classifier-Bi directional LSTM in Keras

The purpose of this repository is to build and train a bidirectional LSTM in order to perform fake news classification. Before feeding a textual dataset into a sequence model (RNN, LSTM, BiLSTM, GRU, etc.), the text dataset needs to be converted to sequences of vectors which needs lots of preprocessing on the dataset. This repository shows all these required operations in a step-by-step procedure.

In summary, this repository performs the following operations:

Importing fake and real news datasets with Pandas and checking sizes and null values
Exploring the imported dataset and feature engineering
Performing data cleaning
Visualizing the cleaned dataset
Preparing the dataset for training by performing tokenization and padding
Build and train a bidirectional LSTM model
Evaluating the model performance
