<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN">
<html>
<head>
  <H2># Diabetic-Retinopathy-Detection-Model-Dr.SMit-BOT</H2>
 
</head>
<body>
<h4>Purpose and Objective:</h4>
  <p>This is informative as well as assistive to diabetic / non-diabetic patients to detect whether they have retinopathy problems or not. This will open up a window to diagnose or start treatment.</p>
<h5>Table of Contents:</h5>
  <li>Dataset obtaining</li>
  <li>Data Preprocess</li>
  <li>Load images</li>
  <li>Resize Images</li>
  <li>Check Class Imbalance</li>
  <li>Model Architecture</li>
  <li>Web Deployment</li>
  <li>Limitation</li>  

<h4>Datasets:</h4>
  <li>For Image Classification : From Kaggle.com </li>
  <li>For Web Scrapping : MedicineNet</li>

<h4>Installation </h4>
  <li><a href="https://www.anaconda.com/">download  Anaconda </li></a>
  <li><a href="https://www.anaconda.com/">python3.9</li></a>
  <li><a href= "https://www.tensorflow.org/">Tensorflow & keras</li></a>
  <li><a href= "https://docs.opencv.org/">OpenCV</li></a>
  <li><a href= "https://anvil.works/">Anvil connection for Deployment</li></a>
  <li><a href= "https://www.sqlite.org/index.html)/">sqllite3 for DataBase</li></a>
  
<h4>Loading and Preprocessing</h4>
<p>This NLP Model has been processed on the local machine and all the Image classification has also been processed on my personal laptop.
A database has been created to keep track of all the questions that the ChatBot is not trained to answer. The Model has been updated on a regular basis and re-trained the model as usual;</p>
<h4>Resize All Images</h4>
<p>As I downloaded from kaggle.com, all the images were in different sizes. I created Height and Width columns for each image and resized the images to the average height and width using openCV before feeding them to the model</p>
<h4>Class Imbalance</h4>
<p>For data imbalance, data augmentation to the dataset using an image data generator with Keras, first checked the distribution of data. The frequency are same or not.</p>
<h4>Training the Model</h4>
<p>After trying different methods to train the classification model, ResNet50 has been used for feature extraction of the data and applied to the augmented data for training. For the NLP, I also used fasttext to handle any out-of-vocabulary text using fasttext representation algorithm.</p>
<h4>Web Deployment</h4>
<p>For The Web App I tried to host it on anvil.works, initially the Dr.SMit Bot.  Initially, the payment option has not been updated monthly basis. So it is a free app hosted there. </p>
<h4>Limitations & Future thoughts</h4>
<p>
<li>To make my App receivable to all the people with their regional languages</li>
<li>To make my App receivable to all the people with speech recognition facilities</li>
<h4>Author</h4>
  <p>Sarmita Majumdar</p>

<p>website: https://www.sarmitamajumdar.com</p>
<p>LinkedIn: https://www.linkedin.com/in/sarmitamajumdar/</p>
<p>email: sarmita.majumdar@gmail.com</p>


