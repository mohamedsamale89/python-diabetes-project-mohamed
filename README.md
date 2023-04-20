#  Machine learning project mohamed s 
 Analyzing and compare the effectiveness of four machine learning algorithms in predicting the onset of diabetes using the Pima Indians diabetes dataset.

# Introduction
Diabetes has emerged as a rapidly growing chronic disease, and its incidence has surged to alarming levels in recent years.. This is due to numerous factors including nutritional habits, lifestyle choices, and genetics. There are 2 types of diabetes which are insulin-dependent diabetes mellitus(type 1 diabetes) and non-insulin-dependent diabetes mellitus(type 2 diabetes) with type 2 diabetes being the most common This has propelled it to become a major global cause of mortality. The sharp increase in this chronic disease has led the need for an effect prognosis tool to diagnose diabetes at an early stage potentially reducing complications and costs. Machine learning effectively be that prognosis tool needed.
The Pima Indians Diabetes Dataset is a dataset that originates from the National Institute of Diabetes and Digestive and Kidney Diseases. It aims to diagnose whether a patient has diabetes or not based on some diagnostic measures involved in the dataset. The dataset is made up of several independent medical predictor variables and one dependent target variable, Outcome. Independent variables comprise the BMI, count of pregnancies the patient has, their level of insulin, age, etc.
We have applied various machine learning algorithms including logsistic,KNN,SVM, and decisoon tree to predict the outcome of diabetes based on this dataset. Overall, this study will examine and determine which machine algorithm performs best.

#Software

The group selected to used Google Colaboratory as the Python software to conduct the final project report. Google Colaboratory, commonly referred to as "Colab," is a popular product from Google Research that enables users to write and execute Python code directly through a web browser. Currently, the group selected the free version of Google Colab.

#dataset

The Dataset used in this study is the Pima Indians diabetes dataset. The objective of the dataset is to predict if women develop diabetes based on a variety of body measurements. The dataset was collected in the1980s and contains information about the Pima Indian population living in the city of Phoenix in the United States. In the dataset provided, there are 8 features in total. These include ;

Bmi,- body mass index(weight in kg)
age - age of women in years
skin thickness- skin fold thickness
 blood pressure-diastolic blood pressure
Pregnancy-Number of times women have been pregnant
 insulin levels- serum insulin levels
 glucose levels-
 pedigree function- a chart related in inheritance of diabetes


The outcome being examined is diabetes which fall under the class column in the dataset. The dataset has a total of 768instances. The dataset can be found on https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

#Data preprocessing 

In this study we thoroughly examined the Pima diabetes dataset. To fill any missing values, we filled in the missing data using the following code; df=fillna(method= ‘ffill’). We also standardized the data used the standard scaler function. By using the standard scalar function, the dataset is scaled resulting in a standard deviation of 1 and mean of zero. In the Pima Indians datasets, features are scaled differently which may negatively impact the accuracy of the model. To avoid this, we standardized the data which would improve the overall performance of the algorithms 

#Feature selection 

In our study, we concluded that all features in the dataset were relevant to the study. The features, which all are medical predictor variables, all play an important role when the outcome of diabetes is considered. Therefore, no features were excluded from the training and testing dataset. 





