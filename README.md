# Used-Car-Price-Prediction
Kodluyoruz Izmir Data Science Bootcamp Capstone Project 

We use dataset from Kaggle for used car price prediction.
Dataset : https://www.kaggle.com/austinreese/craigslist-carstrucks-data/notebooks

We tried to predict the price range of used cars given the features by doing multi-class classification. 
First we preprocess and remove some NA values and outliers. Discard features that are not relevant for the prediction of the price ranges.
Secondly, we encoded data with label encoding and ordinal encoding methods. 
Third, we made six price ranges, which means six price classes. 
Finally, we apply random forest, xgboost, gradient boosting and decision tree
models on the preprocessed dataset with features as inputs and the price ranges as output.
We also used GridSearchCV to find best parameters for our models. 
