# CD-Renewal-Classifier
Classification model that predicts if a CD would be renewed or not.

## Install
This project requires Python 3 and the following Python libraries installed:

- NumPy
- Pandas
- scikit-learn
- Seaborn

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select the Python 3 installer .

## Code
Code is provided in the model.ipynb notebook file. You will also be required to use the data.csv dataset file to run the code. 

## Data
* The data set has 21,321 instances and 23 features (input variables), which include the Certificate of Deposit’s maturity term, times it got renewed, age of the cd, federal rate, rate spread, and some categorical grouping of the cd's indicators, etc.
* The predictor variable (“y”) states the outcome of the CD renewal — whether the respondent would renewal for a deposit 1 (“yes”) or 0 (“no”).
Let's start with loading all the third-party libraries (you can also requirements.txt) that we are going to use and the data set itself

## Contents 
- [1 Exploratory Data Analysis](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=be805de6a9d574720d634d9aa7d103a928f7a75c&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f486172696b61416e6368612f43442d52656e6577616c2d436c61737369666965722f626538303564653661396435373437323064363334643961613764313033613932386637613735632f4d6f64656c2e6970796e62&nwo=HarikaAncha%2FCD-Renewal-Classifier&path=Model.ipynb&repository_id=334535459&repository_type=Repository#Exploratory-Data-Analysis)
  * [1.1 Understanding Data](#11-Understanding Data)
  * [1.2 Identifying Missing Values](#12-Identifying Missing Values)
  * [1.3 Categorical Variables](#13-Categorical Variables)
  * [1.4 Numerical Data Analysis](#14-Numerical Data Analysis)
- [2 Feature Creation](#2-Feature Creation)
- [3 Feature Selection](#3-Feature Selection)
  * [3.1 Label Encoding](#31-Label Encoding)
  * [3.2 Feature Importance Calculation](#32-Feature Importance Calculation)
- [4 Model Development](#4-Model Development)
  * [4.1 80-20 Train & Test Set](#41-80-20 Train & Test Set)
