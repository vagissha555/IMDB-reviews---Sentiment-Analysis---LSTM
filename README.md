IMDB-reviews---Sentiment-Analysis---LSTM

IMDB Reviews Sentiment Analysis using LSTM : This project demonstrates sentiment analysis on the IMDB movie reviews dataset using a Long Short-Term Memory (LSTM) neural network. The model classifies each review as either positive or negative based on its content.

Project Overview : Dataset: IMDB movie reviews, with 50,000 reviews evenly split into training and testing sets. Objective: To build a deep learning model capable of understanding and classifying the sentiment (positive/negative) of movie reviews. Model Used: LSTM (Long Short-Term Memory), a type of Recurrent Neural Network (RNN) well-suited for sequential data like text.

Features : Text pre-processing using Tokenizer and pad_sequences. Neural network architecture: Embedding Layer LSTM Layer Dense Output Layer with Sigmoid Activation Training using binary_crossentropy loss and adam optimizer. Performance evaluated using accuracy and loss metrics on both training and test sets.

Results : The model achieves 87% accuracy on the test set and generalizes well for unseen data, demonstrating the power of LSTM in natural language processing tasks.
