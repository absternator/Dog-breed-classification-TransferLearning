# Multi-class Dog breed Classification 🐶
This notebook builds a multi-class image classification model using Tensforflow and Tensorflow Hub. 

## 1. Problem 
Identify the breed of a dog given an image of a dog.

> If i take a photo of a dog, i want to know what breed of dog it is?
## 2. Data
The data is from the kaggle dog [breed identification competition](https://www.kaggle.com/c/dog-breed-identification/data)
## 3. Evaluation 
The evaluation is a submission file that containst the probabilites for each dog breed for each test image.

Submissions are evaluated on Multi Class Log Loss between the predicted probability and the observed targe
## 4. Features 
- All data is in images 
- There are 120 breeds of dogs(120 classes)
- There are 10,000+ images in training and test sets. Train sets have labels, whilst test set does not. This is because we want to predict the test set. 
