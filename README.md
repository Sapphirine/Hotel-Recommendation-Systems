
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

pywFM, https://github.com/jfloff/pywFM.

xgboost, https://github.com/dmlc/xgboost.

## Code
### project.py
In the project.py file, first we import all libraries and show a simple example of applying Factorization Machine as well as the data structure. Then we do data pre-processing work and divide the data set into train set and test set. The following parts are applying Model I (Random Forest + Popularity Ranking)and Model II (Factorization Machine + XGBoost).

### UI 
If you want to know more about our project, you can open ui-typography.html and
then you can use the website to see our projects. The website includes four parts. The ui-typography.html is the overview part and
home page. The data part includes two part: data overview (table.html) and
descriptive analysis charts (activity.html). The model part includes two parts:
Model1 (rf.html) and Model 2(xg.html) and The conclusion part is the message.html.
