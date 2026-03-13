# plant-disease-detection-cnn
Plant Disease Detection using CNN trained on the PlantVillage dataset to classify plant leaf diseases using TensorFlow and Keras.
## Project Overview

This project focuses on detecting plant diseases from leaf images using Deep Learning. 
A Convolutional Neural Network (CNN) model was trained to classify different plant diseases 
from the PlantVillage dataset.

The goal of this project is to help farmers and agricultural experts quickly identify plant 
diseases using image-based diagnosis.
**MODEL - Convolutional Neural Network**

## Dataset

The dataset used for this project is the PlantVillage dataset obtained from Kaggle.

Dataset Features:
- Contains thousands of leaf images
- Includes multiple plant species
- Each image is labeled with a specific disease or healthy class

The images were preprocessed and resized before training the model.

## Model Architecture

The model is built using a Convolutional Neural Network (CNN) architecture.

Key layers used in the model:

- Convolutional Layers for feature extraction
- MaxPooling Layers for dimensionality reduction
- Flatten Layer
- Dense Fully Connected Layers
- Softmax output layer for classification

- ## Training

The model was trained using the following configuration:

- Framework: TensorFlow / Keras
- Image size: 224x224
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Epochs: 7
- Batch Size: 32

- ## Results

The trained CNN model achieved high accuracy in detecting plant diseases.

Training Accuracy: 92%
Validation Accuracy: 89%

The model is able to classify plant diseases effectively from leaf images.

## Future Work

Possible improvements for this project include:

- Increasing the dataset size for better generalization
- Using advanced CNN architectures like ResNet or EfficientNet
- Deploying the model as a web application using Flask
- Creating a mobile app for farmers to upload leaf images
  
