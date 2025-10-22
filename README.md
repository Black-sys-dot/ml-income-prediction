# ml-income-prediction

![Python](https://img.shields.io/badge/python-3.11-blue)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.3.0-green)
![XGBoost](https://img.shields.io/badge/xgboost-1.7.6-orange)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

Predict if someone makes >50K from census data. ML stuff.

Basically, this project tries to guess if a person makes more than 50K a year based on some census data. Also, we compare a bunch of ML models to see which one’s better.  

## Dataset
Adult income dataset link:  
https://www.kaggle.com/datasets/wenruliu/adult-income-dataset 

## What I did
- Loaded the data  
- Dropped the useless column (`fnlwgt`)  
- Turned categorical stuff into numbers  
- Split into train/test  
- Scaled the numbers  
- Tried different ML models and compared them:  
  - Logistic Regression  
  - SVM  
  - Decision Tree  
  - Random Forest  
  - XGBoost  
- Checked accuracy & confusion matrices  

## How to run
1. Clone this repo  
2. Install dependencies:  
```bash
pip install pandas numpy scikit-learn matplotlib xgboost