# CD-Renewal-Classifier
Classification Model that predicts if a CD would be renewed or not.

## Install
This project requires Python 3 and the following Python libraries installed:

NumPy
Pandas
scikit-learn
Seaborn

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select the Python 3 installer .

## Code
Code is provided in the model.ipynb notebook file. You will also be required to use the data.csv dataset file to run the code. 

## Data
* The data set has 21,321 instances and 23 features (input variables), which include the Certificate of Deposit’s maturity term, times it got renewed, age of the cd, federal rate, rate spread, and some categorical grouping of the cd's indicators, etc.
* The predictor variable (“y”) states the outcome of the CD renewal — whether the respondent would renewal for a deposit 1 (“yes”) or 0 (“no”).
Let's start with loading all the third-party libraries (you can also requirements.txt) that we are going to use and the data set itself

## Contents 
1  Exploratory Data Analysis
1.1  Understanding Data
1.2  Identifying Missing Values
1.3  Categorical Variables
1.4  Numerical Data Analysis
2  Feature Creation
3  Feature Selection
3.1  Label Encoding
3.2  Feature Importance Calculation
4  Model Development
4.1  80-20 Train & Test Set
4.2  70-30 Train & Test Set
5  Validation
6  Other Models
6.1  Model 1: Logistic Regression
6.2  Model 2 - SVM Classifier
6.3  Model 3 - Balanced Dataset Model
7  Future Improvement
