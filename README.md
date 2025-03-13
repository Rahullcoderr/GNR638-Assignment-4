# GNR638-Assignment-4
Theory assignment and Coding assignment both are in this repo.

Rahul B 22b3976

Akash Sansugu Palaniswami (21D171001)


# CNN Model Training for Image Classification

## Overview
This project implements a Convolutional Neural Network (CNN) for image classification using TensorFlow and Keras. The dataset consists of multiple classes stored in separate folders, and the model is trained using different optimizers to compare performance.

## Steps Involved

### 1. Data Handling & Preprocessing
- Mount Google Drive to access the dataset.
- Extract the ZIP file containing images.
- Split the dataset into training (70%), validation (20%), and test (10%) sets.
- Apply image augmentation to improve generalization.
- Convert images into TensorFlow datasets and normalize them.

### 2. CNN Model Development
- Construct a CNN with multiple convolutional and pooling layers.
- Use an activation function (ReLU) for non-linearity.
- Apply softmax activation in the output layer to classify images into different categories.

### 3. Training with Multiple Optimizers
- Train the model using different optimizers: `SGD`, `Adam`, `RMSprop`, etc.
- Run the training process for **50 epochs** for each optimizer.
- Compare optimizer performance using accuracy and loss curves.

### 4. Performance Analysis & Visualization
- Plot training and validation accuracy/loss for each optimizer.
- Display sample images from the dataset to verify correctness.

## Key Features
- **Automated Data Loading**: Reads images and assigns labels automatically.
- **Efficient Training**: Uses batching for faster computation.
- **Hyperparameter Experimentation**: Tests multiple optimizers for best results.
- **Visualization**: Plots results for easy analysis.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- Google Colab (recommended for easy dataset handling)

## Usage
1. Upload your dataset to Google Drive.
2. Modify the dataset path in the script.
3. Run the notebook to train and evaluate the model.
4. Observe optimizer performance and select the best one.

## Results
Adamax, Adam, Nadam gives very good validation accuracy of 80%, and these are the best optimizers for this dataset and our architecture



