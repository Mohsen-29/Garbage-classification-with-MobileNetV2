# Garbage-classification-with-MobileNetV2

## Overview
This repository contains a garbage sorting model implemented using the MobileNetV2 architecture. The model is trained to classify images into 12 different categories representing various types of garbage.

## Link to the used dataset
https://www.kaggle.com/datasets/mostafaabla/garbage-classification

## Model Architecture
MobileNetV2 Base: The model utilizes the MobileNetV2 architecture as its base, followed by a Global Average Pooling layer.

Dense Layer: A Dense layer with 12 output nodes for classification.

## Training
The model is trained for 20 epochs, achieving a peak validation accuracy of 90.14%. The training process involves optimizing the categorical crossentropy loss using the Adam optimizer.

## Usage
The trained model weights are saved in the repository.
Use the provided notebook to load the model and make predictions on new images.

## Results
Peak Validation Accuracy: 90.14%
Training Time: Approximately 1 hour.
Feel free to explore the notebook for more details on the model architecture, training process, and usage.
