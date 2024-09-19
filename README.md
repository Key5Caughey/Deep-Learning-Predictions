# Deep-Learning-Analysis 

## Finding success for a non-profit using deep-learning

## BACKGROUND
From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With machine learning and neural networks, use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

![tf_playground_deep_points](https://github.com/user-attachments/assets/6bb3df4f-b174-451c-9e4e-b3106ac2a199)


## Tools and Techniques Used
**Python, Pandas, NmPy, Sklearn, TensorFlow/Keras, Matplotlib**
- Data Preprocessing, Data Cleaning, StandardScaler, Data Splitting
- Build Neural Network, Compile Model, Train Model, Evaluate Model, Experiment with Hyperparameters

### Preprocess Data
 Read in the charity_data.csv file,identify targets and features for model. Drop columns with irrelevant data. Use get dummies to encode categorical variables, split into features array and target array. Split into training and testing datasets.

### Compile, Train, and Evaluate the Model
 Create neural network, choose hidden layers, neuron amount, epochs,output layer and appropiate activation function. Compile and train model, evaluate test data, export results to an HDF5 file.

### Optimize the Model
  Adjust model, dropping columns, add or reduce neurons/epochs/hidden layers, use different activation functions.

### Report on Model
 Overview, Results, Summary

### Resources
Class notes, Office hours, Tutor, Chatgpt,Google
