![Screenshot (289)](https://github.com/youssef665/AI-ML-projects/assets/110295462/5a63097a-fa44-4b02-9b2a-ca36496bab03)<br>
![Screenshot (294)](https://github.com/youssef665/AI-ML-projects/assets/110295462/d253ae08-9c70-4fa6-9f1b-2aa3202e39dc)<br>
![Screenshot (290)](https://github.com/youssef665/AI-ML-projects/assets/110295462/23c374e4-266e-46b2-8f7f-e4f2104b87e2)<br>

German Traffic Sign Recognition Project
This project aims to recognize German traffic signs using Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN).

Description
The project involves the following key steps and components:

Data Preprocessing
The traffic sign images are preprocessed to ensure they are suitable for training the models. This involves resizing the images, normalizing pixel values, and encoding labels.

Models Used
Artificial Neural Network (ANN): Achieved an accuracy of 95%.
Convolutional Neural Network (CNN): Achieved an accuracy of 99%.
Training and Evaluation
Cross-Validation: Used to ensure the model's robustness and to prevent overfitting.
Confusion Matrix: Generated to evaluate the performance of the models and to visualize the classification results.
Loss and Accuracy Plots: Created to monitor the training process and to compare the performance of ANN and CNN.
Libraries and Tools Used
TensorFlow: For building and training the neural network models.
Keras: A high-level API for TensorFlow to simplify model creation.
NumPy: For numerical operations and handling arrays.
Matplotlib: For plotting graphs and visualizing data.
OS: For handling file operations.
CV2: For image processing tasks.
PIL: For additional image processing.
Scikit-learn: For preprocessing, model evaluation, and cross-validation.
Warnings: To suppress unnecessary warnings during execution.
Code Imports
The following libraries and tools were used in the project:

python
Copy code
import tensorflow as tf
from tensorflow.keras import regularizers
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Dense, Dropout, Activation, Flatten, Conv2D, MaxPooling2D
import numpy as np
import matplotlib.pyplot as plt
import os
import cv2
from sklearn.preprocessing import LabelEncoder
from sklearn.model_selection import train_test_split
import warnings
from PIL import Image
from sklearn.metrics import confusion_matrix
import itertools
warnings.filterwarnings('ignore')
import keras
from sklearn.model_selection import StratifiedKFold
By following these steps, the project demonstrates an effective approach to recognizing traffic signs using deep learning techniques. The comparison between ANN and CNN highlights the superior performance of CNN in image classification tasks.

This project showcases the application of machine learning and image processing techniques to solve a real-world problem, achieving high accuracy and providing valuable insights into the performance of different neural network architectures.