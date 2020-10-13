# BREAST POWER Awareness - Model on Breast Cancer 
![Singapore](https://github.com/sanashar/singapore_airbnb_modelling/blob/main/heat_map.png)

# Overview 
Breast cancer is a significant public health problem in today’s society. It is one of the most common cancers among women worldwide, representing the majority of new cancer cases and cancer-related deaths according to global statistics. The early diagnosis can improve the prognosis and chance of survival, as it can promote timely clinical treatment to patients. Furthermore, accurate classification of benign tumors can prevent patients undergoing unnecessary treatments. In this project I will develop a machine learning algorithm that can predict the discrete class of breast cancer using test and training approach. 

# Project Goal

# Repository Navigation
Technical Notebook               : [Notebook](https://github.com/sanashar/singapore_airbnb_modelling/tree/main/Notebooks)

Report       : [Summary Report](https://github.com/sanashar/singapore_airbnb_modelling/tree/main/Summary%20Report)

Presentation       : [PowerPoint](https://github.com/sanashar/singapore_airbnb_modelling/tree/main/Data)


# Data Summary
This is the Breast Cancer Wisconsin dataset, created by Dr. William H. Wolberg. I will be using loading the data from [sklearn.data](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) website, but it is also available on [UCI Machine Learning](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) website and [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data). It has 569 entries and 30 columns. 

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



# Project Info
DATA 602 Project 1 - Sana Sharma

Languages    : Python

Tools/IDE    : Anaconda

Libraries    : pandas, matplotlib, statsmodels, sklearn
