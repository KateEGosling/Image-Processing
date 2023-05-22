# Image-Processing

## Description:
This project uses supervised machine learning to train a model to make predictions using the MNIST database of handwritten
digits.

## Table of Contents
- [Installation](#inst)
- [Usage Instructions - Create train, test and development sets](#train_test_set)
- [Usage Instructions - Random Forrest Creation](#random_forrest)
- [Usage Instructions - Confusion Matrix](#confusion_matrix)

<a name="inst"></a>
## 1. Installation

### Import Packages for dataframe, visualisations and models:
- import scipy.io
- import numpy as np
- import pandas as pd
- import matplotlib.pyplot as plt
%matplotlib inline

### Import dataset
The dataset can be downloaded from here: https://www.kaggle.com/datasets/hojjatk/mnist-dataset 

<a name="train_test_set"></a>
## 2. Load the data set and create test, training and dev samples:
- Train set: provide examples to train the model
- Development set: used as an interim test of the model once fit to the training set
- Test set: final set of unseen data to test the performance of the fully trained model


<a name="random_forrest"></a>
## 3. Create a random forrest:
- Tune the model using max depth parameter to avoid over-fitting the model
- Plot the max-depth scores to select best-depth to be used
![download](https://github.com/KateEGosling/Image-Processing/assets/123898068/6c5522b3-a8a7-48af-9b1a-6ab569a4c5d8)


<a name="confusion_matrix"></a>
## 4. Confusion Matrix:
- Plot a Confusion Matrix to identify extent and spread of false positives
![download](https://github.com/KateEGosling/Image-Processing/assets/123898068/11442702-a5d2-4376-a9e0-3e87915d8496)

