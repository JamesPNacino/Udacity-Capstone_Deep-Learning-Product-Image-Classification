# Udacity-MachineLearningCapstone

## Capstone Project, Machine Learning Engineer NanoDegree

I participated in a Kaggle competition for my Udacity capstone project. Kaggle is home to data science competitions.
https://www.kaggle.com/c/cdiscount-image-classification-challenge

### Summary 

This project is to use deep learning to classify product images. Cdiscount provided their product images and would like to improve their accuracy when classifying the images into respective categories. This project is to use deep learning to train a model which can accurately predict the various images into their respective category.

### Python Packages Required to Load in Environment - Install
Note: These packages and step by step walkthrough of running this project are found in the 'Capstone Report.ipynb' file

import numpy as np

import pandas as pd

import tensorflow as tf

import keras

from keras.layers import Conv2D, MaxPooling2D, GlobalAveragePooling2D

from keras.layers import Dropout, Flatten, Dense

from keras.models import Sequential

import h5py

from subprocess import check_output

iport io

import bson

from matplotlib.pyploat as plot

from skimage.data import imread

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. This project was also immplemented using Python 3.

### Code
To implement this code and train the models in this project you would have to follow the step by step instructions in the file 'Capstone Report.ipynb'. 

### Run
In a terminal or command window, navigate to the top-level project directory customer_segments/ (that contains this README) and run one of the following commands:

ipython notebook customer_segments.ipynb

### Setting up CUDA GPU computing with Tensorflow

In this following video are the steps I took to use get my GPU to start training neural networks.
https://www.youtube.com/watch?v=io6Ajf5XkaM

I have used a NVIDIA GTX 1070 GPU for this project to speed up computing times.

### Data Required for this project
All the data is found in the link below.
This project consists of image data provided by Cdiscount (an Amazon-like company). The goal is to classify Cdiscount's online products into their respective categories

https://www.kaggle.com/c/cdiscount-image-classification-challenge/data
