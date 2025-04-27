# Fashion MNIST - SVM Classifier

## Overview
This project aims to classify images of clothing items from the Fashion MNIST dataset using a Support Vector Machine (SVM) model. It is part of my machine learning learning journey.

## Dataset
The **Fashion MNIST** dataset is a collection of 70,000 grayscale images of 28x28 pixels, categorized into 10 different classes (e.g., T-shirt, Trouser, Pullover, Dress, Coat, etc.).  

## Project Structure
- **Data Loading**:
  - Loading the Fashion MNIST dataset.
- **Data Preprocessing**:
  - Normalizing pixel values.
  - Flattening the images for SVM input.
- **Model Building**:
  - Training an SVM classifier using the `sklearn` library.
- **Model Evaluation**:
  - Evaluating the model using accuracy score, classification report, and confusion matrix.
  - Visualizing model performance.

## Model accuracy
The model used here is a SVM Classifier from the sklearn library. The achieved accuracy of 87% indicates that the model performs well in predicting based on the selected features.
