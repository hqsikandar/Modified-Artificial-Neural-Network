This repository contains the code and resources for a novel artificial neural network (ANN) model designed to enhance the accuracy of stock exchange trend predictions. The model is based on a new architecture that applies activation functions both before and after each layer, significantly improving the network's performance in handling the complexity and non-linearity of stock market data.

Overview
Predicting stock market trends is a challenging task due to the inherent uncertainty and complexity of the market. Traditional machine learning and deep learning techniques have often struggled to achieve high accuracy in this domain. This project proposes a modified ANN model that introduces pre- and post-activation functions to better capture market trends and improve prediction accuracy.

Key Features
Enhanced ANN Architecture: The model uses activation functions both before and after each layer, optimizing the network's ability to process complex, non-linear stock market data.
Improved Backpropagation Algorithm: A newly developed backpropagation algorithm is incorporated, enabling faster training and more accurate predictions.
Comprehensive Evaluation: The model's performance is evaluated using various metrics, including Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE).
Data
The dataset used in this project is sourced from Kaggle and contains 104,225 records from different stock exchange market trends. The data is split into a 70-30 ratio for training and testing purposes.

Stages of Implementation
Data Pre-processing: The raw data undergoes extensive pre-processing to improve its quality and suitability for training the neural network.
Model Training: The pre-processed data is used to train the modified ANN model, leveraging the new activation function approach.
Prediction and Evaluation: The trained model predicts stock market trends, and its accuracy is evaluated using the aforementioned performance metrics.
Usage
This repository provides the implementation of the proposed ANN model, including scripts for data pre-processing, model training, and performance evaluation.
