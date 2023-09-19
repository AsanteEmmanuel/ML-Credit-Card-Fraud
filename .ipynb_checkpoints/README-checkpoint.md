# ML-Credit-Card-Fraud
This project aims to predict fraudulent credit card transactions using various classification models.

## Data 
The data is a combination of credit card transactions over years 2018 - 2022 (Check Kaggle).

## Models
The models implemented are Logistic Regression, Random Forest and Support Vector Machine. I employ cross-validation to get more robust estimates of the best model. The better performing model turned out to be the Logistic regression model.


## Evaluation
* I employ the recall score as the main evaluation metric because it is more appropriate in the context of the problem.

* After employing grid search and cross validation over the parameter space, the average best Recall score was ~92.45%.

* This means that of the actual fraudulent transactions, the model is a predict is to be fraudulent with a 92.45% probability.

* Below is a table of the eveluation metric results for the various candidate models that were implemented.

