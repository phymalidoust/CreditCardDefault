#  Contents
This directory includes python modules (Jupyter notebook) to address the defaulting on credit card payments in ABC international bank.

### **A.** ``credit_card_data.xlsx``
This file contains information provided by the bank. It includes personal and bank account information of customers, default, and payment bill dates.
### **B.** ``preparing_db.ipynb``
The data file provided contains several defects that must be fixed before performing any analysis and making conclusions/predictions for the bank.
This python file fixed the defects and prepared the database for further analysis.
The fixed database is stored in a new file `**database_fixed.xlsx**'.
### **C.** ``pair_correlations_01.ipynb`` , ``pair_correlations_02.ipynb``
The file with 01 index determines the correlation between each pair of entries in the fixed database, including all components. It helps to identify patterns and potential sources of defaults occurring. When largest dependencies are found, the file with index 02 reperforms the pair correlation investigation with fewer components, omitting uncorrelated components to default making. 
### **D.** ``predictive_models.ipynb``
This file examines three different predictive models to the credit card payment default and proposes the best one according to the efficiency of the models and the main purpose of the prediction, which is the prediction if a customer fails in a future payment or not.
<br />
The models examined are:
<br />
1- Logistic Regression
<br />
2- Decision Tree Classifier
<br />
3- Gaussian Naive Bayes
<br />
<br />
