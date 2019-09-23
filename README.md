# Taxifare-prediction
Predicting taxi fares using 1 hidden layer neural network:

This is my first attempt on building a neural network model to make predictions.
Dataset is taken from kaggle. Link is here: https://www.kaggle.com/chicago/chicago-taxi-rides-2016
This dataset includes taxi trips for 2016, reported to the City of Chicago in its role as a regulatory agency. 
The features used to make predictions are trip_miles, pickup and drop-off location, time of the day
and whether it is weekday or weekend.
There are three jupyter notebooks. The first one is used for merging all the csv files and selecting the taxi company with largest
number of records.
Second one is for data preprocessing. It involves selectiong the necessary features and altering some of the columns to
reduce the number of features and include only necessary ones.
Third one is for category encoding(one hot encoding) and building the neural network with one hidden layer.
Third notebook is suggested to be used with Google Colab because of the processing time required.
This is an ongoing project. The final goal is to use the model for directing the taxis to place themselves in given location at
a given timestamp to maximize the taxi company's revenue.
All constructive feedbacks are more than welcome.
