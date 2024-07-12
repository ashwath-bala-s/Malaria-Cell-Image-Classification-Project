# Malaria-Cell-Image-Classification-Project

**Introduction:**

Malaria is a life-threatening disease caused by parasites transmitted through the bites of infected mosquitoes. Traditionally, diagnosis involves microscopic examination of blood smears, which can be time-consuming and dependent on the expertise of healthcare professionals. This project aims to utilize machine learning techniques to automate the detection of malaria from blood images, improving diagnostic efficiency and accuracy.

**Problem Statement:**

The objective of this project is to identify from blood smears using machine learning to predict whether the sample is taken from an infected person or not.

**Dataset:**

The Dataset used for this Project has 19,290 Images and corresponding rows in a CSV, which has following Variables:

filename: FileName of an Image Sample

label: Mentions Whether a blood sample is Malaria infected or not [Target Variable]

**Project Description:**

• Examined and visualized the images to identify patterns and class distributions in the Malaria Detection Dataset.

• Performed label encoding and resized images to 40x40 pixels, flattening them into feature vectors for modelling.

• Achieved a model accuracy of 77% using a Linear SVM model with pixel values as features.

• Utilized Histogram of Oriented Gradients (HOG) features for images resized to 128x64 pixels, enhancing feature representation.

• Achieved a model accuracy of 81% with a Logistic Regression model using HOG features.

**Observation:**

•	Hog Features are able to extract more information when compared to Pixel Features, on detecting whether a blood sample is infected or not. 

**Skills:** Machine Learning · Data Pre-Processing · Image Pre-Preprocessing · Feature Extraction · Logistic Regression · Linear SVM · Pixel Feature Extraction · HOG Feature Extraction
