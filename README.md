# Hotel-Recommendation-Systems

Columbia University E6893 Big Data Analytics final project: Hotel Recommendation Systems

Group member: Audrey Ya-tzu Lee, Qiang Fei, Yihao Lin

## Data Source

In the Kaggle Expedia Hotel Recommendations competiton, Expedia has provided logs of customer behavior. These include what customers searched for, how they interacted with search results (click/book), whether or not the search result was a travel package.

https://www.kaggle.com/c/expedia-hotel-recommendations/data

## Installing

We create a virtual machine with 24 vCPUs and 300 GB memory by Google Compute Engine, and run all the models in Ubuntu 16.04 with Python 2.7. Here is a tuturial to set up the system:

Amulya Aankul: https://towardsdatascience.com/running-jupyter-notebook-in-google-cloud-platform-in-15-min-61e16da34d52

To run the python code first follow the instruction in GitHub to install the pywFM and XGBoost library. 

"pywFM," [Online]. Available: https://github.com/jfloff/pywFM.

"xgboost," [Online]. Available: https://github.com/dmlc/xgboost.

## Code
In the project.py file, first we import all libraries and show a simple example of applying Factorization Machine as well as the data structure. Then we do data pre-processing work and divide the data set into train set and test set. The following parts are applying Model I (Random Forest + Popularity Ranking)and Model II (Factorization Machine + XGBoost).
