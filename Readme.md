# Machine Learning with Python Project
## Predicting House Prices Using Linear Regression Model

### Objective:
  The aim of this project is to predict house prices using Python scikit-learn library and Linear Regression algorithm. This project is an intermediate ML project. For this project, a ML pipeline is created. Feature transformation, feature selection, training, and testing phases are applied.

### Dataset:
  Data set contains information from the Ames Assessorís Office used in computing assessed values for individual residential properties sold in Ames, IA from 2006 to 2010.
  Tab characters are used to separate variables in the data file. The data has 82 columns which include 23 nominal, 23 ordinal, 14 discrete, and 20 continuous variables (and 2 additional observation identifiers).

### Analyses
  * The dataset is explored and cleaned. Missing values were handled:   
  1) The columns having more than 5% missing values were dropped   
  2) The text columns having more than 1 missing row were dropped  
  * Extensive feature transformation were applied:  
  1) The features that are not useful and the features that leak data were eliminated.  
  2) New features were created.
  * Best features to predict the Sale Price were found.  
  1) The categorical features with low variance and the features with a few unique values were eliminated.  
  2) The numerical features that have low correlation with the target value were eliminated. Alternative correlation treshold values were applied o find the best model.
  3) The categorical values were dummy-coded.
   * A Regression Model was created to predict Sale Prices.   
  1) Alternative parameters were applied (parameter tuning) for the pipeline.  
  2) Kfold cross validation method was used to find the best model and handle over-fitting.
