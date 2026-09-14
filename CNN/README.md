# ANN Implementation

In this folder, I learned the fundamentals of **Convolutional Neural Networks (CNNs)** and implemented the concepts practically to understand how CNNs process and classify images.

## Concepts Learned

* What is Convolutional Neural Network (CNN)
* Why CNNs are used for image data
* Convolution Operation
* CNN Layers
* Filters & Feature Maps
* Padding
* Stride
* Pooling Layers
* Flatten Layer
* Fully Connected Layers
* CNN Architecture
* Image Feature Extraction

##  CNN Layers

Studied how different layers work together to extract features from images.

* Convolutional Layer
* Activation Layer
* Pooling Layer
* Flatten Layer
* Fully Connected / Dense Layer
* Output Layer

Also implemented and experimented with **4 CNN layers** to understand how features are progressively extracted from input images.

## Padding & Stride

Learned how **padding** and **stride** affect the output size and feature extraction process.

* Valid Padding
* Same Padding
* Stride
* Output Feature Map Dimensions

## Pooling

Studied pooling techniques used to reduce spatial dimensions while retaining important features.

* Max Pooling
* Average Pooling
* Purpose of Pooling
* Effect of Pooling on Feature Maps

## Flatten Layer

Learned how the **Flatten layer** converts 2D/3D feature maps into a 1D vector so that the extracted features can be passed to fully connected layers for classification.

## CNN Architecture

### Core CNN Flow

```text
Input Image
    ↓
Convolution
    ↓
Activation
    ↓
Convolution
    ↓
Pooling
    ↓
Convolution
    ↓
Pooling
    ↓
Flatten
    ↓
Dense Layer
    ↓
Output / Prediction
```

## Mini Project

Implemented a small **CNN-based image classification project** to apply the concepts learned and understand the complete workflow of building, training, and evaluating a CNN model.

### Project Workflow

```text
Image Dataset
     ↓
Preprocessing
     ↓
CNN Model
     ↓
Feature Extraction
     ↓
Flatten
     ↓
Classification
     ↓
Prediction
```

## Goal

The goal of this folder was to understand the fundamentals of **CNNs and image-based deep learning** and gain practical experience by implementing a CNN model from scratch using the concepts learned.
