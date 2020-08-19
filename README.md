# Recurrent Neural Network for Rain Forecasting

This repository builds a model to predict whether or not it will rain tomorrow in Australia using real-world weather data using Recurrent Neural Network with PyTorch. the dataset contains daily weather observations from numerous Australian weather stations, the target is to answer a simple question, which is: Will it rain tomorrow? The dataset can be found on [Kaggle](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)

It starts by preprocessing then converting the data to tensors, then building the neural network model with pytorch, then using a loss function and an optimiser to train the model and finally evaluating the model. 
