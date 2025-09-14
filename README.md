# Kaggle_MNIST
Notebook with a CNN model aiming to recognize handwritten numbers of the MNIST dataset
Info and data: https://www.kaggle.com/c/digit-recognizer

# Contents

Kaggle_MNIST_notebook.ipynb – main notebook with data loading, preprocessing, model training, and evaluation.

Modeling: Neural network built with TensorFlow/Keras.

Evaluation metric: Accuracy, as used in Kaggle submissions.

# Features

Loads the MNIST dataset provided by Kaggle (train.csv, test.csv).

Performs preprocessing (normalization, reshaping).

Defines a Convolutional Neural Network (CNN) using Keras.

Trains and validates the model on a training/validation split.

Generates predictions for Kaggle submission.

Packages used:

numpy

pandas

matplotlib

scikit-learn

tensorflow / keras

# Results

The trained CNN achieves an accuracy of 99.11 on the validation set. The final predictions on the test set are saved in submission.csv.

