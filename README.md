# Sparkify-Predict-Customer-churn


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project requires Python 3.x and the following Python libraries installed:

pyspark, datetime, numpy, matplot, pandas and seaborn

## Project Motivation<a name="motivation"></a>

For this project we have predicted churn rates for the Sparkify music service. Sparkify is assumed to be a popular digital music service where users can stream their songs using either free-tier or premium subscription model. The users have options to upgrade, downgrade and cancel the service. It is important for the Sparkify to predict the users actions so that can it can prevent users from cancelling or downgrading its services.

The motivation for this project is to predict the customers that are more likely to churn based on their behaviors on the Sparkify. We are using Pyspark for the project.

## File Descriptions <a name="files"></a>

1. Sparkify - Predict customer churn.ipynb

This code present in Jupyter notebook was used to explore a smaller subset with Spark in Udacity workspace. Udacity workspace contains a tiny subset (128MB) of the full dataset available (12GB). 
The code is structured into following sections:
  i) Load & Clean dataset
  
  ii) Exploratory Data Analysis including churn & downgrade identification
  
  iii) Feature Engineering
  
  iv) Modeling

2. Project README file

3. Link to the blogpost
https://medium.com/p/cebba12d2a81/edit

## Results<a name="results"></a>
After testing out three machine learning methods SVM, Logic regression and random forest method:
Training score for all three models is around ~66% but Random Forest model has highest accuracy/ F1-score ~74% of three models

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to udacity for the dat as part of udacity course. 
Feel free use the code and other info in this repo for all your references whenever required.
