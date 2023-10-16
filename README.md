# Diabetic-Retinopathy-Detection-Model-Dr.SMit-BOT

Purpose and Objective:
This is informative as well as assistive to diabetic / non-diabetic patients to detect whether they have retinopathy problems or not.  This will open up a window to diagnose or start treatment.

Table of Contents:

Dataset obtaining
Data Preprocess
Load images
Resize Images
Check Class Imbalance
Model Architecture
Web Deployment
Limitation


Datasets:
For Image Classification: Datasets are downloaded from Kaggle 
For Web Scrapping: Used MedicineNet

Installation 
Anaconda
Python 3.9(Above)
Tensorflow & Keras
Visualization: matplotlib
OpenCV for cleaning 
Anvil for Deploy
sqllite3 for DataBase

Loading and Preprocessing
The NLP Model was processed on Google Colab while the Image classification was processed on my personal machine.
A database was created to keep track of all the questions that the Bot was not trained to answer. The Model is updated every day by retraining the model

Images are Resized
The images were of different sizes. I created Height and width columns for each image and resized the images to the average height and width using openCV before feeding them to the model

Class Imbalance
Applied data augmentation to the dataset using an image data generator with Keras, I

Training the Model:
After trying different methods to train the classification model, ResNet50 was used for feature extraction applied on the augmented data to train the image classification model. For the natural language processing, I used fasttext to handle any out-of-vocabulary text using the fasttext representation algorithm.

Web Deployment
The web app is hosted on anvil.works retinopathyBOT. This involves writing some Java Script with Python. Hopefully, the app is still up and running by the time you are reading this readme. This is because of the monthly payment to host the web app on anvil.works

Limitations
The speech recognition API currently works on Firefox and Chrome browser
Cloud deployment costs money, so the app might not be on for a long time
Authors
Omolewa Davids

website
LinkedIn
