# Hotel-Recommendation-Systems

Columbia University E6893 Big Data Analytics final project: Hotel Recommendation Systems

Group member: Audrey Ya-tzu Lee, Qiang Fei, Yihao Lin

## Data Source

Expedia has provided logs of customer behavior. These include what customers searched for, how they interacted with search results (click/book), whether or not the search result was a travel package.

https://www.kaggle.com/c/expedia-hotel-recommendations/data

## Installing

To run the python code first follow the instruction in GitHub[1][2] to install the pywFM and XGBoost library. 


[1] "pywFM," [Online]. Available: https://github.com/jfloff/pywFM.

[2] "xgboost," [Online]. Available: https://github.com/dmlc/xgboost.

## Code
In the project.py file, first we import all libraries and show a simple example of applying Factorization Machine as well as the data structure. Then we do data pre-processing work and divide the data set into train set and test set. The following parts are applying Model I (Random Forest + Popularity Ranking)and Model II (Factorization Machine + XGBoost).
