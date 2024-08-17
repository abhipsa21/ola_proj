PROJECT TITLE - Ola Bike Ride Request Demand Forecast
GOAL - The aim of the project is to make a forecast of the demand in Ola Bike Rental Services. The dataset contains 2 years data different features that are responsible for fluctuations in the customer ride request demand for training the model. This project predicts the upcoming nature of the customer request demand.

WHAT HAVE I DONE

Loading datasets
Handling null values
Changing into datetime format
Mapping key values to Dictionary
Performing Exploratory Data Analysis
Distribution of target variable 'count'
Visualizing the Demand using multiple variables
Visualization of the continuous varibles using Histogram
Visualization of the Correlation Matrix of continuous features and understanding how it will affect the Target variable
Visualization of the Correlation Matrix of all the independent features
Data Preprocessing
Performing One Hot Encoding on categorical features
Dropping the features with low correlation¶
Visualization of the Correlation Matrix of the preprocessed data
Splitting the data
Using Linear Regression(Accuracy - 86.55%)
Using Decision Tree(Accuracy - 99.03%)
Using Hypertuned KNN(Accuracy - 99.32%)
Using Hypertuned Random Forest(Accuracy - 99.995%)

Saving the Hypertuned Random Forest Regressor and XGBoost Regressor models to get predictions from the test set.
Loading the saved models
Loading the test data
Getting the predictions using the pre trained hypertuned Random Forest model
Getting the predictions using the pre trained hypertuned Random Forest model
Saving the predictions in a dataset
MODELS USED

Linear Regression - A machine learning algorithm based on supervised learning. It performs a regression task. Regression models a target prediction value based on independent variables. It is mostly used for finding out the relationship between variables and forecasting.
XGBoost - eXtreme Gradient Boost algorithm is based on the Gradient Boosting model which uses the boosting technique of ensemble learning where the underfitted data of the weak learners are passed on to the strong learners to increase the strength and accuracy of the model.
Decision Tree - This algorithm works on the basis of creating tree structures to take decisions
KNNs - * An algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories.*
Random Forest - This algorithm works on the concept of emsemble learning.It used bagging technique to train multiple predictors on the same sampled instances to achieve a higher degree of accuracy.

LIBRARIES NEEDED

numpy
pandas
matplotlib
seaborn
scikit-learn
datetime
calender
pickle

Conclusion
In this project we have performed a detailed analysis and visualization of the training dataset with different Exploratory Data Analysis techniques. Then a comaprative analysis of different Regressons have been done to predict the request demand of Bike Rental Services.After performing the model comparative analysis we can conclude that almost all the models had an accuracy above 99% except the Linear Regressor. The Hypertuned Random Forest Regressor gave best result with 99.995% accuracy


















