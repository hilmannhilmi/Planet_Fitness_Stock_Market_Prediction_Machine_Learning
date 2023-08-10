# Introduction
This project focuses on evaluating machine learning models to forecast stock market trends for Planet Fitness. Using historical stock price data, the project analyzes and predicts the adjusted closing prices, employing statistical and machine learning techniques.

# Dataset
The dataset consists of Planet Fitness's historical stock price data, including features such as the date and adjusted closing price. The data is sourced from the CSV file named 'PLNT.csv'.

# Methodology
The project follows these key steps:

##### Data Visualization: 
Plotting the historical adjusted closing prices. /n
##### Data Splitting: 
Dividing the data into training and testing sets based on date ranges. The first four years are used for training, and the fifth year is used for testing./n
##### Model Training: 
Training a Linear Regression model to understand the relationship between the year and adjusted closing price.
##### Prediction: 
Making predictions for the fifth year using the trained model.
##### Evaluation: 
Calculating the Mean Squared Error (MSE) to evaluate the model's accuracy.
##### Result Plotting: 
Visualizing the predicted and actual adjusted closing prices for the fifth year.
##### Results:
The project successfully predicts the adjusted closing prices for Planet Fitness for the fifth year using a Linear Regression model, SVM and Random Forest. The best machine learning algorithms that provides the highest accuracy is Random Forest with MSE at 3.87 after some feature engineering has been done. The predictions are visualized alongside the actual values, and the model's performance is evaluated using the mean squared error.

# How to Run
Ensure that you have the required dependencies installed.
Load the dataset from the specified CSV file.
Run the Jupyter Notebook to visualize the data, train the model, make predictions, and evaluate the results.

# Dependencies
1. Python 3.x
2. Pandas
3. NumPy
4. Scikit-Learn
5. Matplotlib
