# Car-Make-Classification

## Overview
This project investigates a deep learning approach for image classification, focusing on the detection and recognition of car makes using the ResNet50 architecture. The project systematically examines the role of data augmentation in improving classification performance and addressing class imbalance in the CompCars dataset, which contains over 11,000 images of various car models and car makes.

## Dataset
The project uses the CompCars dataset, which contains 11,059 images across various car models and parts. The dataset is split into training, validation, and test sets for rigorous performance evaluation. You can download the dataset from the following link: [CompCars Dataset](http://mmlab.ie.cuhk.edu.hk/)

## Results
The car make classification task was performed using the ResNet50 architecture, trained both with and without data augmentation, and using two loss functions: cross-entropy and focal loss. The findings highlight the effectiveness of ResNet50 and data augmentation in addressing class imbalance and enhancing classification performance. 

- ResNet50 with cross-entropy loss and data augmentation achieved 68% accuracy on the test set.
