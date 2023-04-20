#  Machine learning project mohamed s 
 Analyzing and compare the effectiveness of four machine learning algorithms in predicting the onset of diabetes using the Pima Indians diabetes dataset.

# Introduction
Diabetes has emerged as a rapidly growing chronic disease, and its incidence has surged to alarming levels in recent years.. This is due to numerous factors including nutritional habits, lifestyle choices, and genetics. There are 2 types of diabetes which are insulin-dependent diabetes mellitus(type 1 diabetes) and non-insulin-dependent diabetes mellitus(type 2 diabetes) with type 2 diabetes being the most common This has propelled it to become a major global cause of mortality. The sharp increase in this chronic disease has led the need for an effect prognosis tool to diagnose diabetes at an early stage potentially reducing complications and costs. Machine learning effectively be that prognosis tool needed.
The Pima Indians Diabetes Dataset is a dataset that originates from the National Institute of Diabetes and Digestive and Kidney Diseases. It aims to diagnose whether a patient has diabetes or not based on some diagnostic measures involved in the dataset. The dataset is made up of several independent medical predictor variables and one dependent target variable, Outcome. Independent variables comprise the BMI, count of pregnancies the patient has, their level of insulin, age, etc.
We have applied various machine learning algorithms including logsistic,KNN,SVM, and decisoon tree to predict the outcome of diabetes based on this dataset. Overall, this study will examine and determine which machine algorithm performs best.

#Software

The group selected to used Google Colaboratory as the Python software to conduct the final project report. Google Colaboratory, commonly referred to as "Colab," is a popular product from Google Research that enables users to write and execute Python code directly through a web browser. Currently, the group selected the free version of Google Colab.

#dataset

The Dataset used in this study is the Pima Indians diabetes dataset. The objective of the dataset is to predict if women develop diabetes based on a variety of body measurements. The dataset was collected in the1980s and contains information about the Pima Indian population living in the city of Phoenix in the United States. In the dataset provided, there are 8 features in total. Pregnancies, plasma glucose concentration, Blood Pressure, Skin Thickness: Insulin, MI, Diabetes Pedigree Function: Age and the Outcome: Class variable :diabetes. The dataset can be found at https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

#findings
In our study we used 4 machine learning algorithms which were logistic regression, knn, Support vector machine, and a decision tree. Based on the performance measurements on the testing dataset, we concluded that the best performing model was the logistic regression model which had an accuracy of %77.92. The second-best performing model was the support vector machine which had an accuracy of %74.89. The knn model had an accuracy of %74.68and the decision tree model had an accuracy of %63.59.  The confusion matrix displayed for the optimal logistic regression model indicated that the model predicted 132 true negatives and 48 true positives correctly. It also predicted 14 false positives and 37 false negatives. Overall, the confusion matrix indicates that the model performed well. The confusion matrix displayed for the support vector machine predicted 123 true negatives and 50 true positives correctly. It also predicted 28 false positives and 30 false negatives. The decision tree confusion matrix displayed a prediction of 36 true negatives and 11 true positives correctly. It also predicted 44 false positives and 40 false negatives. The optimal knn model correctly predicted 133 true negatives and 42 true positives. It also predicted 17 false positives and 39 false negatives. Based on the accuracy of the models along with the confusion matrix and the performance measurements displayed above, we can conclude that the optimal model with the best overall performance was the logistic regression model. This result contracts some of the result already published used similar algorithms. 















