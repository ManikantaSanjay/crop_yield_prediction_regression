# Hey there, green thumbs! 🌱👍

Welcome to our **Crop Yield Prediction Regression** project. This is where we're using the power of machine learning to predict crop yields for 10 of the most consumed crops worldwide. 

## What's it all about? 🤔

We've designed and implemented a crop yield prediction model using various ML approaches. We've used a bunch of ML algorithms including Random-Forest Regressor, Gradient-Boosting Regressor, Decision-Tree Regressor, and Support-Vector Regressor.

## How does it work? 🛠️

We've gone through a few steps to get to our results:

1. **Gathering and Cleaning Data** - We've removed unwanted columns from the CSV files, dropped the null valued rows, and merged the yield CSV file with the pesticides and average rainfall CSV files to form a combined dataframe with all the required attributes.

2. **Data Exploration** - We've used visual exploration to understand the dataset and see the correlation between the different attributes.

3. **Data Preprocessing** - We've encoded categorical variables, scaled the features, and split the data into a 70:30 train-test ratio.

4. **Model Training, Comparison, and Selection** - We've trained our model using Gradient Boosting Regressor, Random Forest Regressor, SVM, and Decision Tree Regressor. We've used the R^2 (coefficient of determination) regression score function for evaluation. The Decision Tree Regressor gave us the best accuracy of 96.04%.

5. **Model Results & Conclusions** - We've visualized the importance of the top 7 features in determining the crop yield, and viewed the yield predicted for the top 10 most consumed crops. We've also used the Graphviz Library to see the decision tree created by the model.

## Libraries we've used 📚

1. NumPy
2. Pandas
3. Matplotlib
4. Scikit-learn
5. Seaborn
6. Pydot
7. Graphviz

## Check it out! 📖

You can find the notebook for this project [here](https://github.com/ManikantaSanjay/crop_yield_prediction_regression/blob/master/crop_yield_prediction_ml.ipynb).

## Dataset 📊

We've used data from [FAO](http://www.fao.org/home/en/) and [World Bank](https://data.worldbank.org/).

So, that's about it! If you like what you see, give us a star ⭐. Thanks and happy coding! 🚀
