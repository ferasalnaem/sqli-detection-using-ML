# sqli-detection-using-ML
This experiment is a research project about applying Machine Learning approaches to detect SQL Injection attacks. Below is a description about all notebooks and parts of this project:  
1. SQLIA_kaggle_Dataset.ipynb :

   The first part of the project was applying ML algorithms like Logistic Regression, Support vector machines, Decision Trees and Random forests on the a dataset token from kaggle. https://www.kaggle.com/syedsaqlainhussain/sql-injection-dataset?select=sqliv2.csv

2. The second part was building my own dataset and applying ML on it:

    2.1 buildingMyDataset.ipynb:
    I have collected some payloads and benign data from different repositories and built a dataset, which contains sql injections queries and normal data. The benign data has normal texts and also some valid SQL queries, so that I could reduce the false positives in this way.
  
    2.2 SQLI_onMyOwnDataset.ipynb:
    Logistic Regression, Support Vector machines, Decision Trees and Random Forests were here applied 
    
    2.3 SQLI_using_LSTM_onMyOwnDataset.ipynb:
    In this notebook I also applied LSTM on my dataset
