# Neural-Networks

- Started learning about Neural Networks - their intuitions, and implementation in python using scikit-learn and tensorflow.

## Day - 01
### ANN:
- Implemented a very simple Artificial Neural Network with 2 hidden layers inorder to predict whether a customer would exit a bank or not.
- Used rectifier function as the activation function for the hidden layers.
- Used sigmoid function for the output layer.
  
### Adult Salary Classifier
- Dataset used: https://archive.ics.uci.edu/dataset/2/adult
- Preprocessing steps involved:
    - Encoding the target variable
    - One hot encoding categorical columns
    - Feature scaling all numerical columns
- ANN Compiled using:
    - optimizer = adam optimizer
    - loss function = binary_crossentropy
    - metrics = accuracy

## Day - 02
### Cat or Dog Classifier:
- Implemented my first Convolutional neural network using tensorflow on a dataset of cats and dogs.
- Training set - comprised of 4000 images of cats and 4000 images of dogs.
- Testing set - comprised of 2000 images of cats and 2000 images of dogs.
- It is a binary classification problem so the loss function used was binary-crossentropy.
- Adam optimizer was used.
  
