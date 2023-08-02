# Regression-Module
The Regression Module is a Python package that takes inputs of molecular fingerprints or SMILES and outputs the performance of four regression models: Linear Regression, Gaussian Process Regression, Decision Tree Regression, and Random Forest Regression. The models' performance is quantitatively measured through statistics, specifically R^2, MSE, MAE, and R Pearson Correlation Coefficient values. 

# Code Versions:
I created multiple versions of both the fingerprint and SMILES versions of this code to create various run times. For larger data sets, the Regression_Metrics code can take multiple hours to run. Therefore, if a rough estimate is all the user requires, they can use the Fast_Regression_Metrics code in order to gain these results without waiting as long for results.

**Fast_Regression_Metrics:**
Optimization of the four regression models is removed from the code to give less accurate but faster results.

**Regession_Metrics:**
Some parameters are optimized, but for models that take longer to process (namely Gaussian Process Regression and Decision Tree Regression) only one or two parameters are optimized to prevent the code from running for excessive amounts of time.

**Slow_Regression_Metrics:**
In this version of the code, more optimized parameters are included, meaning the code will take longer to run but produce stronger results.

**Regression_Metrics_Graphs**
This version outputs the same statistics but also outputs graphs of each regression model's performance. On the x-axis are the values predicted by the model and on the y-axis are the true values.
