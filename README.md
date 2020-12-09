# CS2020-IntroductionDataScience 

This repository provides the explonation and classification/clusterization solution for **customer credit risk** task.

# Description
The solution is represented with 3 sub tasks:
1. Develop a prediction model to classify the customers as good or bad
2. Cluster the customers into various groups
3. Provide ideas on how frequent pattern mining could be utilized to uncover some patterns in the data and/or to enhance the classification


# Dataset
Dataset consist of 1000 records (1000 customers), where each customer is represented with `20 features` and `target values`: {1 - good customer;  2 - bad customer}

## Features
Features description can be found in  `data_description.txt` file. 

## Models Comparison
|#       |dataset_v0_catboost_v0|dataset_v1_catboost_v0|dataset_v1_catboost_v1|dataset_v1_xgboost_classifier_v0|dataset_v1_xgboost_classifier_v1|
|---     |---                   |---                   |---                    |---                            |---                             |
|accuracy|0.736667              |0.962857              |0.968571               |0.967143	                     |0.962857                        |
          			

				

