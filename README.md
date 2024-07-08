# Cat Breed Classifier (Siamese vs Sphynx) using OpenCV and Machine Learning

## Introduction

This project aims to develop an image classifier that can distinguish between two specific cat breeds (Siamese and Sphynx) using the Oxford-IIIT Pet Dataset. The focus of this project is to utilize the functionalities of OpenCV to create a feature extractor and subsequently train a machine learning model with these features. The primary goal is not to achieve the most accurate model but to understand and improve the process of extracting and refining information from image data.

## Project Overview

### 1. Importing Libraries

The project begins by importing necessary libraries such as OpenCV, NumPy, Matplotlib, and Scikit-learn. These libraries are essential for image processing, feature extraction, and building machine learning models.

### 2. Loading and Visualizing Images

Images from the dataset are loaded and visualized to understand their structure and characteristics. This step helps in identifying the preprocessing techniques required for the images.

### 3. Defining and Creating Preprocessing Functions

Several preprocessing functions are defined to prepare the images for feature extraction. These functions include adjusting brightness and contrast, applying masks to remove backgrounds, highlighting gray tones, and applying Fourier transforms.

### 4. Defining and Creating a Pipeline Class

A `Pipeline` class is created to encapsulate the entire process of loading images, applying preprocessing functions, augmenting data, extracting features, training, and evaluating the model. This class helps in organizing the code and making the process modular.

### 5. Training and Evaluating the Model

The pipeline is used to train a machine learning model. Different preprocessing strategies are attempted to find the best approach for distinguishing between Siamese and Sphynx cats. The performance of the model is evaluated using various metrics such as accuracy, precision, recall, F1 score, and AUC.

### 6. Predictions on Test Images

A method is added to the `Pipeline` class to predict labels for images in a test folder. This method loads test images, preprocesses them, extracts features, and predicts their labels. The results are then displayed with the true and predicted labels.

### 7. Conclusion

A summary of the project's findings and the performance of the best model is provided. Potential future improvements are also discussed.

