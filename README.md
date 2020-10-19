# BREAST POWER Awareness - Model on Breast Cancer 
![October](https://github.com/sanashar/breast_power_proejct1/blob/main/october_pic.jpg)

# Overview 
Breast cancer is a significant public health problem in today’s society. It is one of the most common cancers among women worldwide, representing the majority of new cancer cases and cancer-related deaths according to global statistics. The early diagnosis can improve the prognosis and chance of survival, as it can promote timely clinical treatment to patients. Furthermore, accurate classification of benign tumors can prevent patients undergoing unnecessary treatments. In this project, I will use four machine learning algorithms: Logistic Regression, K-Nearest Neighbors, Decision Tree and Random Forest to create models for Breast Cancer prediction and compare which has the best accuracy score though testing and training. 

# Project Goal
Through my research, the goal is that the highest performing model may eventually be used to create an AI tool to assist clinicians in Breast Cancer screening and detection. This research study aims to address following research question -

Which ML model from this study best enables the prediction of BC using the classification algorithm of supervised learning by testing and training the data?

# Motivation & Background
Model selection is the most exciting phase in Applying Machine Learning to any dataset and is also known as algorithm selection for predicting the best results. So I will use classification algorithm of supervised learning and the highest performing model can assist clinicians in detecting BC. Many researchers have used classification and data mining methods so far, and have concluded that ML is an effective way to classify data. Especially in medical field, these methods have been used to predict and to make decisions. Thus, the correct diagnosis of breast cancer and classification of patients into malignant or benign groups is the subject of much research.

# Repository Navigation 

Table of Contents -

Technical Notebook               : [Notebook](https://github.com/sanashar/breast_power_project1/tree/main/notebooks)

Report       : [Summary Report](https://github.com/sanashar/breast_power_project1/tree/main/reports)

Presentation       : [PowerPoint](https://github.com/sanashar/breast_power_project1/tree/main/presentation)

Youtube Presentation       : [Link](https://youtu.be/kNzVvZ2gWks)


# Data Summary
This is the Breast Cancer Wisconsin dataset, created by Dr. William H. Wolberg. I will be loading the data from [sklearn.data](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) website, but it is also available on [UCI Machine Learning](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) website and [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data). It has 569 entries and 30 columns. 

  Attribute Information:
1) ID number
2) Diagnosis (M/0 = malignant, B/1 = benign)

Ten real-valued features are computed for each cell nucleus:
1) radius (mean of distances from center to points on the perimeter)
2) texture (standard deviation of gray-scale values)
3) perimeter
4) area
5) smoothness (local variation in radius lengths)
6) compactness (perimeter^2 / area - 1.0)
7) concavity (severity of concave portions of the contour)
8) concave points (number of concave portions of the contour)
9) symmetry
10) fractal dimension ("coastline approximation" - 1)



# Project Info & Software Requirements
DATA 602 Project 1 - Sana Sharma

Languages    : Python 2.7

Tools/IDE    : Anaconda

Libraries    : pandas, matplotlib, statsmodels, sklearn, seaborn
