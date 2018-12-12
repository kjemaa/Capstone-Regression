# Capstone: Price prediction in the London Airbnb market


The project has been conducted in Jupyter notebook.

Following libraries were used:
- pandas
- numpy
- matplotlib
- sklearn
- datetime
- xgboost

Data were collected on:
http://insideairbnb.com/get-the-data.html

Files:
- listings.csv
- calendar.csv
- proposal.pdf
- report.pdf
- capstone.ipynb

## Excecutive summary
 
The project shows how to develop a regressor to recommend prices in the airbnb market in London. 

It starts with a data exploration phase where important variables are visualized. 
Then data are preprocessed and cleaned to fit the machine learning algorithms we will apply later. 
The feature engineering part is extensive, including a selection of which features to keep, transform and scale.
Before a dimensionality reduction is tried by applying PCA to the dataset. 

A benchmark model - Ridge linear model - is fitted both to the PCA dataset and the full feature dataset. 
And a pool of models were measured against the benchmark. The full feature dataset had much better results than the PCA dataset. 
And XGboost proved to be the best model and chosen for parameter tuning. 
The parameter tuning resulted in a R square of 0.78., which is a satisfying result, although several other measured 
could have been taken to improve the model given more time and computing power. 

## Aknowledgements
Resources are cited in the report and in the notebook

