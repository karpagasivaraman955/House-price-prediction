House Price Prediction using Machine Learning
Project Overview
This project predicts house prices based on various features such as area, number of bedrooms, bathrooms, and amenities using Linear Regression.
It uses a real-world dataset (Housing.csv) with both numerical and categorical features.

Dataset Features
Feature	Description
price	House price (Target)
area	Area in square feet
bedrooms	Number of bedrooms
bathrooms	Number of bathrooms
stories	Number of floors/stories
mainroad	Is on main road (yes/no)
guestroom	Has guestroom (yes/no)
basement	Has basement (yes/no)
hotwaterheating	Has hot water heating (yes/no)
airconditioning	Has air conditioning (yes/no)
parking	Number of parking spaces
prefarea	Preferred area (yes/no)
furnishingstatus	Furnishing status (furnished/semi-furnished/unfurnished)

Technologies Used
Python

Pandas

NumPy

Scikit-Learn

Matplotlib

Seaborn

Steps Performed
Data Preprocessing

Handled categorical features with Label Encoding

Split dataset into Train and Test sets

Model Training

Trained Linear Regression on the training set

Model Evaluation

Calculated Mean Squared Error (MSE)

Visualized Actual vs Predicted Prices

Plotted Residuals to analyze error distribution

Prediction Example

Predicted price of a house based on user-input features

Visualizations Included
Actual vs Predicted Price Scatter Plot

Residual Error Distribution Plot

Feature Importance Bar Chart

