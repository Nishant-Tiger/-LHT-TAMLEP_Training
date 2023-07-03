# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.

## To excute the script
python non_standardcode.py

## How to run  non_standardcode.py script code?
1. Create a new conda environment mle-dev.
2. Install the packages numpy, pandas, matplotlib, seaborn and scikit-learn.
3. The function call fetch_housing_data() is missing, it will give error while calling loading function. So, we have to call this function after defining, so that it can retrieve from github.
4. This python file is kind of designed as jupyter notebook, so we may have to print some output variables like RMSE, MAE, etc. for different regressors.
5. Also, we may have to comment matplotlib plots, as running it in Ubuntu sometime cause plugin issues.
