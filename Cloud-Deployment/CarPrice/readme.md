# About Project
[CarDekho](www.CarDekho.com) is India's leading car search venture that helps users buy cars that are right for them. Its website and app carry rich automotive content such as expert reviews, detailed specs and prices, comparisons as well as videos and pictures of all car brands and models available in India. The company has tie-ups with many auto manufacturers, more than 4000 car dealers and numerous financial institutions to facilitate the purchase of vehicles.

This data is basically extracted from Kaggle and can be used for a lot of purposes but in my project, I have used this data for predicting the Selling price of car by using the Random Forest Regressor Algorithm in Machine Learning.

#### *Note : This project is purely for the purpose of demonstrating my Machine Learning skills to the hiring organization on a beginners level.* 

##  About Data
The columns in the given dataset is as follows:
- Car_Name (This column is filled with the name of the car.)
- Year (This column is filled with the year in which the car was bought)
- Selling_Price (This column is filled with the price the owner wants to sell the car at.)
- Present_Price (This is the current ex-showroom price of the car.)
- Kms_Driven (This is the distance travelled by the car till date in kilometers.)
- Fuel_Type (Fuel type of the car)
- Seller_Type (This column tells us whether the seller is a dealer or an individual.)
- Transmission (This column tells whether the car is manual or automatic.)
- Owner (This column tells us about the number of owners the car has previously had. Forexample, 2nd Hand, 3rd Hand, 4th Hand owners etc)

My Response Variable is Selling Price.

I have performed the complete End-to-End Machine Learning (i.e, from Identifying the Problem to Final Model Deployment in Cloud)

Demo  : [Car Price](https://car-python-deployment.herokuapp.com/)

Please look into the Demo for Deployment.

# Steps Involved in solving the Problem.(Lifecycle of the Machine Learning Problem)

- Identified the Problem Statement (Here the Problem statement is to Predict the Selling Price of the Used Cars by considering various factors like Age of Car, Fuel type, Car type etc.)
- Imported all the Necessary Libraries to Solve this Problem.
- Imported the Raw Data (In CSV format)
- Performed the Exploratory Data Analysis
- Performed Data Cleaning (Removing the Null Vaues)
- Performed Feature Engineering on "Year Purchased (Year)" and "Current Year" and created a new column called "Age". [Age = Current Year - Year Purchased]
- Performed One Hot Encoding and also avoided the Dummy Variable Trap on all the Categorical Variables. Also removed the columns "Car Name" column because it's just a normal name.
- Performed Correlation to findout the relationship between variables.
- Performed the Train-Test-Split
- Trained the Random Forest Regressor model on Training data.
- Performed Hyperparameter tuning using the RandomizedSearchCV to identify the optimal parameters for training model.
- Retrained the model with optimal Hyperparameters.
- Predicted the Selling Price of the Car by applying the Test Dataset to our trained model.
- Calculated the Values of Performance Metrics for Regression (MAE, R2-ERROR, RMSE etc)


## Steps Involved in Deployment of my Model.
- Saved our Python Notebook as Pickle File.
- Taken help of my Colleague to create a Web App using the flask framework.
- Taken help of my colleague in preparing the HTML file for displaying the Web Page.
- Created the Requirements.txt file and ProcFile.
- Commited the Code in Github.
- Linked my Github to Heroku.
- Deployed my model in Heroku (Manual Deployment of my Master Branch)
- Web App is Ready ([Car Price](https://car-python-deployment.herokuapp.com/))
