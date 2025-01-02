# Day---8-Digit-recognition-using-RANDOM-FOREST
I have taken a challenge to make project on every algorithm of Machine Learning. [ Day - 8 | Digit recognition using RANDOM FOREST]
Project Overview
This project focuses on recognizing handwritten digits from images using the Random Forest algorithm. The dataset used is the MNIST dataset, which contains 28x28 pixel grayscale images of handwritten digits (0-9). The objective of this project is to train a Random Forest classifier to predict the digit based on the pixel values in the image.

Random Forest is an ensemble learning method that combines multiple decision trees to improve the overall model performance. Each tree in the forest makes an independent prediction, and the majority vote (for classification tasks) is used as the final output.

Key Objectives
Preprocess the MNIST dataset: Clean the data, handle missing values (if any), and normalize the images for better performance.
Build a Random Forest Classifier: Train a Random Forest model to classify the handwritten digits based on pixel values.
Evaluate Model Performance: Evaluate the classifier’s performance using accuracy, confusion matrix, and classification report.
Predict New Data: Use the trained model to predict the digit class for new, unseen images.
Algorithm: Random Forest
Random Forest is a powerful ensemble method that builds multiple decision trees and merges them together to get a more accurate and stable prediction. It works by:

Bootstrap Aggregating (Bagging): Creating multiple subsets of the training data (with replacement) and training a separate decision tree for each subset.
Random Feature Selection: Randomly selecting a subset of features for each decision tree, which increases the diversity of trees and reduces overfitting.
Voting: For classification, each tree "votes" for the predicted class, and the class with the majority votes is chosen as the final prediction.
