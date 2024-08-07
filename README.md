# Hand Gesture Recognition Database with CNN

This repository contains a project that utilizes deep learning techniques to classify hand gestures from the Hand Gesture Recognition Database, which is a collection of near-infra-red images of ten distinct hand gestures.

## Overview

In this project, we use end-to-end deep learning to build a classifier for hand gesture images. The dataset comprises ten folders labelled 00 to 09, each containing images of specific gestures. We employ Convolutional Neural Networks (CNN) to recognize these gestures with high accuracy.

## Dataset

The Hand Gesture Recognition Database consists of:
- 10 distinct hand gestures.
- Near-infra-red images.
- 10 folders labelled 00 to 09, each containing subfolders for each gesture.
- Link : https://www.kaggle.com/datasets/gti-upm/leapgestrecog/data

## Preprocessing

The preprocessing involves:
- Reading images from the dataset.
- Converting images to grayscale.
- Resizing images for consistency.
- Normalizing pixel values.

## Model

We use a Convolutional Neural Network (CNN) with the following architecture:
- Convolutional layers with ReLU activation.
- MaxPooling layers.
- Fully connected layers.
- Softmax layer for classification.

## Results

The model achieves an accuracy of 99.9% to 100% on the test set, demonstrating its effectiveness in classifying hand gestures.

## Conclusion

This project illustrates how deep learning can be effectively applied to hand gesture recognition with minimal preprocessing and high accuracy.
