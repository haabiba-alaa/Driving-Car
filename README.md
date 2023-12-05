**Self-Driving Car** 
This repository contains the code and methodology for collecting, loading, and preprocessing data obtained from the Open Source Self-Driving Car project. The primary objective is to utilize this data to predict steering and throttle actions based on images of cars. Two different approaches were explored and implemented, leveraging both TensorFlow Keras and PyTorch frameworks.

## Data Collection

The data used for training and validation was collected through the Open Source Self-Driving Car Udacity platform. This data comprises images of cars along with associated steering and throttle actions.

## Data Preprocessing

Prior to model training, the collected data underwent preprocessing steps to ensure suitability for training the predictive models. This involved procedures such as image normalization, data augmentation, and splitting into appropriate training and validation sets.

## Model Development and Evaluation

### TensorFlow Keras Approach

A model was constructed using the TensorFlow Keras framework to predict steering and throttle actions based on the processed images. The Mean Squared Error (MSE) metric was used to evaluate the performance of this model, achieving an MSE of 0.1045 on the validation set.

### PyTorch Approach

An alternative model was built using the PyTorch framework to accomplish the same prediction task. This model demonstrated a different performance metric, achieving an accuracy of 0.0934 on the validation set.

## Conclusion

This repository showcases two different approaches to predicting steering and throttle actions in self-driving cars based on image data. Both TensorFlow Keras and PyTorch frameworks were employed, achieving competitive performance metrics.
