# Iris-Species-Classification
Iris Species Classification
Machine Learning Task: Iris Species Classification
## Goal
build a machine learning model that can classify the species of iris flowers based on their features

Dataset
➔ You are provided with a dataset in CSV format with the following columns:

◆ Sepal_Length: The length of the sepal.

◆ Sepal_Width: The width of the sepal.

◆ Petal_Length: The length of the petal.

◆ Petal_Width: The width of the petal

◆ Class: The species of the iris (e.g., setosa, versicolor, virginica).

## STEPS:  
◆ first i read data set 

◆ show the columns information (columns names and data types )

◆ see if there's null values in rows
● see the describtion and correlation between the features 
● i used seaborn visulization to show corr heatmap  ( if color brightness (the higher corr ) else (the lower corr)
● then i split datd features and label 
● first model i used KMean cluster unsupervised learning , just use featiures and use elbow method to determine cluster numbers 
● then second models i used svc and LogisticRegression classfication models supervised learning ,split data to test and train 
● show accurcy train and test data , accurcy Model Evaluation ( score between y_actual and y_pred)
● and show Confusion Matrix For Logistic Regression , the good Confusion Matrix beacuse the non diagonal are zaros 

