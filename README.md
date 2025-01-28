# Vision Projects


Welcome to the **Vision Projects** repository! This repository is dedicated to cutting-edge deep learning projects focused on various computer vision tasks. Here, you'll find solutions built with advanced techniques like Convolutional Neural Networks (CNNs) and custom algorithms for the following areas:

- **Food Image Classification:** A CNN-based model to classify food images.
- **Skin Disease Detection:** A CNN model trained to detect skin diseases.
- **Logo Detection:** A custom object detection model designed from scratch to identify logos in images.

## Project Overview

### 1. **Food Image Classification**
A project aimed at classifying food images. This model classifies food items into 101 categories and was developed using CNN techniques. 

- **Dataset:**
- **Technologies Used:** TensorFlow, Keras, OpenCV, NumPy, Matplotlib
- **Main Tasks:**
  - Image preprocessing and augmentation
  - Building and training the CNN model
  - Model evaluation using accuracy and loss metrics
  - Visualization of results and confusion matrix

### 2. **Skin Disease Detection**
A deep learning project focused on detecting skin diseases. The project aims to provide a reliable tool for identifying various skin conditions with high accuracy.

- **Dataset:** 
- **Technologies Used:** TensorFlow, Keras, CNN architectures, Data augmentation
- **Main Tasks:**
  - Data preprocessing and augmentation to handle imbalance in data
  - Training a CNN for skin disease classification
  - Fine-tuning and model optimization for improved performance
  - Evaluation metrics such as accuracy, recall, precision, and F1-score

### 3. **Logo Detection**
This project is focused on detecting logos within images using object detection techniques. Unlike traditional pre-trained models, the detection algorithm has been custom-built from scratch for detecting logos.

- **Dataset:** Custom dataset of logos
- **Technologies Used:** OpenCV, TensorFlow, Keras, custom Haar-cascade algorithm
- **Main Tasks:**
  - Curating and annotating a custom dataset
  - Training a Haar-cascade object detection model for logo recognition
  - Model optimization for detecting logos in different image scenarios
  - Evaluation with precision, recall, and accuracy metrics

## Project Structure
The repository is divided into different folders based on the individual projects:

- `Food-Image-Classification/`: Contains all files related to the food image classification project.
- `Skin-Disease-Detection/`: Contains all files related to the skin disease detection project.
- `Logo-Detection/`: Contains all files related to the custom logo detection project.

## Requirements
Each project folder contains a `requirements.txt` file with the necessary dependencies to run the respective project. Make sure to install the required libraries before running the models.

To install dependencies, run the following command:

```bash
pip install -r requirements.txt

