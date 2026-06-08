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

### Fruit Classifier:
- Downloaded a dataset with more than 10K images of different fruits.
- Many were corrupted files, so spent some time in data cleaning.
- Had to use some images from the training dataset as part of the validation dataset as well. (Caused the model to overfit).
- Added 2 Convolutional layers, 2 pooling layers, 1 flattening layer and output layer.
- Optimizer used - adam
- Loss function used - sparse_categorical_crossentropy
- Metric used: accuracy
- The model completed training with 100% accuracy, which was suspicious.
- While testing, it could classify 1 out of 3 images correctly.
- Classic issue of overfitting.


## Day - 03
### Weapon Classifier
- Downloaded a dataset with many weapon images.
- As part of data cleaning, removed the corrupted files and created subfolders for each weapon type.
- Added 3 Convolutional layers, 3 Pooling layers, 1 Flattening and 1 output layer.
- Optimizer used - adam
- Loss function - sparse_categorical_crossentropy
- Metric used - accuracy
- The model completed training with 82.8% accuracy.
- While testing, it could classify 2 out of 3 images correctly.
