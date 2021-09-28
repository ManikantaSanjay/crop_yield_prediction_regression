# crop_yield_prediction_regression
## Description :
* Designed and Implemented a Crop Yield Prediction model using various ML approaches.
* <b>ML Algorithms Used</b> : Random-Forest Regressor, Gradient-Boosting Regressor, Decision-Tree Regressor, Support-Vector Regressor
* <b>Problem Statement</b> : Predict crops yield for 10 of most consumed crops worldwide.
* <b>Outcome</b> : Decision-Tree Regressor gives an accuracy of 96% and Graphviz is used to create the graph of the Decision Tree.

## Steps Involved :
* Step I - <b>Gathering and Cleaning Data</b> -> Here, we remove the unwanted columns from the csv files; drop the null valued rows; and then we merge the yield csv file with the pesticides and average rainfall csv files to form a combined dataframe containing all the required attributes.
* Step II - <b>Data Exploraton</b> -> Here, we try to use visual exploration to understand what is in the dataset and try to see the correlation between the different attributes present in the dataframe.
* Step III - <b>Data Preprocessing</b> -> Here, we perform encoding categorial variables; scaling the features; and perform train-test-split of the data in a 70:30 ratio.
* Step IV - <b>Model Training, Comparison, and Selection</b> -> Here, we perform training using the following algorithms - Gradient Boosting Regressor, Random Forest Regressor, SVM, Decision Tree Regressor . We make use of the evaluation metric, R^2 (coefficient of determination) regression score function. Among them, Decision Tree Regressor is found to give a better accuracy of 96.04 %.
* Step V - <b> Model Results & Conclusions</b> -> Here, we use visualisation library to view the importance of the top 7 features in determining the yield of the crop, and we view the yield predicted for the top 10 most consumed crops. We make use of the Graphviz Library to see the decision tree created by the model.

## Python Libraries Used :
* NumPy 

* Pandas 

* Matplotlib

* Scikit-learn

* Seaborn 

* Pydot

* Graphviz

## Link to NoteBook : 
https://github.com/ManikantaSanjay/crop_yield_prediction_regression/blob/master/crop_yield_prediction_ml.ipynb 🔗

## Dataset: 👇
http://www.fao.org/home/en/

https://data.worldbank.org/

## Add a star 🌟 to the repo if u like it.😃 Thank You ✌️
