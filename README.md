
# Classify hearth attack possibilites using machine learning


### Contents

1. [Introduction](#introduction) 
2. [Data](#data)
3. [Data preprocessing](#data-preprocessing)
4. [Model](#model)
5. [Evaluation](#evaluation)
6. [Conclusion](#conclusion)
7. [References](#references)

***

### Introduction

There are millions of people in the world who are suffering from heart attacks. In order to help them, we need to 
classify the possible causes of heart attacks. Our goal is to predict the heart attack possibility of a person based on 
their age, sex, cholesterol level, etc.

***

### Data

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date.The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no/less chance of heart attack and 1 = more chance of heart attack

Attribute Information
1) age
2) sex
3) chest pain type (4 values)
4) resting blood pressure
5) serum cholestoral in mg/dl
6)fasting blood sugar > 120 mg/dl
7) resting electrocardiographic results (values 0,1,2)
8) maximum heart rate achieved
9) exercise induced angina
10) oldpeak = ST depression induced by exercise relative to rest
11)the slope of the peak exercise ST segment
12) number of major vessels (0-3) colored by flourosopy
13) thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
14) target: 0= less chance of heart attack 1= more chance of heart attack

Dataset is taken for learning purpose. Source of the data : https://archive.ics.uci.edu/ml/datasets/Heart+Disease

***