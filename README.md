# TRGN_510_FinalProject
<h3>Title:
<h4>"Breast Cancer Diagnosis using KNN".

<h3>Author:
<h4>Aastha Yatin Dave

<h3>Contact:
<h4>davea@usc.edu

<h3>Overview :
  <h4>The aim of this project is to classify malignant and benign tumors from Breast cancer Wisconsin (Diagnostic) dataset using machine learning algorithm KNN.
K-nearest neighbor algorithm is a machine learning algorithm which recognizes pattern to classify the data. 
KNN is normally used for classification and regression and here we are classifying the Breast Cancer data. We are training the model to predict based on the data input whether the cells are Benign or malignant without having to take a look under microscope. Here k is a user defined constant and is based on the distance from the query points.
   For training the model we are taking major part of the dataset (80%) and the rest is used for testing the model. This could automate the process of diagniosis of cancer. I will try to make a machine learning model that can predict the type of cancer with maximum possible accuracy. 

<h3>Data: 
<h4> Breast Cancer Wisconsin (Diagnostic) Dataset 
This data set can be downloaded from UCI machine learning repository. 
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29 
This data set contains :
569 observations with 32 variables. 

<h3>Milestone1:
<h4> To find out how many are benign and malignant cases in the dataset and whether any columns are empty. Check if there is any data which is not required and remove it from the dataset. This might create overfitting of data which might impact negatively on the performance of the model. Since all the data in all the columns are in different scale, normalize the data and bring the value between 0 and 1. 

<h3>Milestone2:
<h4>To prepare data for training and testing set. Use KNN function and try to find out the value of k which gives higher accuracy. Perform confusion matrix and find out the performance of the model. Calculate the accuracy of the model. 

<h3>Deliverables:
<h4> R Markdown
