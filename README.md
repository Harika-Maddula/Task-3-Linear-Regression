This project implements Simple Linear Regression and Multiple Linear Regression to predict house prices using Python.
The goal of this task is to understand how regression models work and how to evaluate their performance.
 Tools Used:
Python
Pandas
NumPy
Matplotlib
Scikit-learn
 Dataset:
I used a House Price Prediction dataset.
The dataset contains features like:
Area
Bedrooms
Bathrooms
Target variable:
Price
 Steps Followed
1. Import Libraries
Imported required libraries for data handling, visualization, and machine learning.
2️. Load Dataset
Loaded the dataset using Pandas.
3. Data Preprocessing
Checked column names
Removed missing values 
Selected required features
4. Simple Linear Regression
Used one feature (Area) to predict Price
Split data into training and testing sets
Trained the model
Predicted house prices
Evaluated model using MAE, MSE, and R² score
Plotted regression line
5. Multiple Linear Regression
Used multiple features (Area, Bedrooms, Bathrooms)
Trained the model again
Evaluated performance
Interpreted coefficients
 Evaluation Metrics Used :
MAE (Mean Absolute Error) → Average prediction error
MSE (Mean Squared Error) → Penalizes larger errors
R² Score → Shows how well the model explains the data
Higher R² score means better model performance.
 Results:
The model was able to predict house prices based on input features.
Multiple Linear Regression performed better than Simple Linear Regression because it uses more features.
