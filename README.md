# Neural_Network_Charity_Analysis


## Overview

In this work, Nural Network Modeling (Deep Learning) was used to help a foundation (Alphabet Soup) to perform loan risk assessment for predicting where to make investments on their applicants using data (in a a CSV) containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization. The data were preprocessed, and split into training and test dataset. The initial neural network models were assesed, and then were optimized with the aim to achieve > 75% accuracy. 

**Tools:**
- Python and Pandas
- Scikit-Learn
- Tensorflow
- Keras tuner
- Git

## Results
- For the initial Neural Network model, 2 hidden layers, and the output model was used as follows.
  - 1st hidden layer: Dense(units=24, input_dim=number_input_features, activation="relu"
  - 2nd hidden layer:Dense(units=12, activation="relu"
  - Output layer: Dense(units=1, activation="sigmoid"
  - The model accuracy = 0.72, loss = 0.56 

Then the model was re-run 3 times as follows.
- 1st try
  - 1st hidden layer: Dense(units=24, input_dim=number_input_features, activation="relu"
  - 2nd hidden layer:Dense(units=12, activation="relu"
  - Output layer: Dense(units=1, activation="sigmoid"
  - The model accuracy = 0.72, loss = 0.56 

- 2nd try
  - 1st hidden layer: Dense(units=24, input_dim=number_input_features, activation="relu"
  - 2nd hidden layer:Dense(units=12, activation="relu"
  - Output layer: Dense(units=1, activation="sigmoid"
  - The model accuracy = 0.72, loss = 0.56 
 
 - 3rd Try
  - 1st hidden layer: Dense(units=24, input_dim=number_input_features, activation="relu"
  - 2nd hidden layer:Dense(units=12, activation="relu"
  - Output layer: Dense(units=1, activation="sigmoid"
  - The model accuracy = 0.72, loss = 0.56 

- Hyperparameter optimization using Keras Tuner
  
# Summary



