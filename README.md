# Used-Car-Price-Prediction
Kodluyoruz Izmir Data Science Bootcamp Capstone Project 

We use dataset from Kaggle for used car price prediction.
</br>Dataset : https://www.kaggle.com/austinreese/craigslist-carstrucks-data/notebooks

We tried to predict the price range of used cars given the features by doing multi-class classification. <br> 
First we discarded features that are not relevant for the prediction of the price ranges. And then dropped some NA values and removed outliers.
<br>Secondly, we encoded data with label encoding and ordinal encoding methods and filled nan values of cylinders, size, type, drive features with Random Forest model.
<br>Third, we made six price ranges, which means six price range classes. 
<br>Finally, we applied random forest, xgboost, gradient boosting and decision tree
<br>models on the preprocessed dataset with features as inputs and the price ranges as output.
<br>We also used GridSearchCV to find best parameters for our models. 
