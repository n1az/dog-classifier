# This deep learning model uses Transfer Learning from TensorFlow Hub with TensorFlow in Google Colab.

## 1. Problem

We are identifying the breed of a dog given an image of dogs.

When I'm sitting at the cafe and I take a picture of a dog, I want to know what breed it is.

## 2. Data

The data we are using is from Kaggle's dog breed identification competition.

## 3. Evaluation

The evaluation is a file prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

## 4. Features

Some information about the data:
* We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
* There are 120 breeds of dogs.
* There are around 10000+ images in the training set. ( These images have labels).
* There are around 10000+ images in the test set. ( these images have no labels, because we'll want to predict them)
