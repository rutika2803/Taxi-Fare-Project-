# Taxi-Fare-Project-
Taxi Fare Prediction Using Regression

1.Introduction:
This project focuses on predicting the fare of a taxi trip based on factors such as distance travelled, trip duration, and number of passengers.
The project uses Supervised Machine Learning and a Regression model to understand the relationship between trip-related factors and taxi fare. Python is used for data preprocessing, exploratory data analysis, visualization, model building, and evaluation.
The main purpose of this project is to demonstrate how statistical and machine learning techniques can be applied to a real-world transportation problem.

 
2.Objectives:
To study the relationship between taxi trip details and fare.
To analyze the given taxi fare dataset.
To perform data preprocessing and exploratory data analysis.
To visualize important patterns in the dataset.
To build a regression model for fare prediction.
To evaluate the performance of the regression model.
To understand the factors that influence taxi fare.


3.Dataset Description:
The dataset contains 500 taxi trip records.
Variables
Variable	Description
Trip_ID -	Unique identification number of the trip
Distance_km	- Distance travelled during the trip in kilometres
Duration_min -	Duration of the trip in minutes
Passenger -	Number of passengers
Fare -	Taxi fare for the trip


4.Target Variable:
Fare is the target variable that the regression model tries to predict.


5.Technologies Used:
Python
Pandas – Data handling and preprocessing
NumPy – Numerical calculations
Matplotlib – Data visualization
Seaborn – Statistical visualization
Scikit-learn – Machine Learning
Jupyter Notebook / Google Colab


6.Data Preprocessing:
The following preprocessing steps were performed:
Checked the dataset for missing values.
Checked for duplicate records.
Examined the data types of variables.
Checked numerical variables for unusual values and outliers.
Prepared the independent and dependent variables for model building.


7.Exploratory Data Analysis:
Exploratory Data Analysis was performed to understand the dataset using:
Mean
Median
Minimum and maximum values
Standard deviation
Correlation analysis
Scatter plots
Distribution plots
Regression plots
The visualizations help identify the relationship between distance, duration, passengers, and fare.


8.Machine Learning Model:
A Regression model was used because the target variable, Fare, is a continuous numerical value.
Independent Variables
Distance_km
Duration_min
Passenger
Dependent Variable
Fare
The dataset was divided into training and testing data. The training data was used to build the model, while the testing data was used to evaluate its performance.


9.Model Evaluation:
The regression model was evaluated using suitable regression evaluation measures such as:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
These measures help determine how accurately the model predicts taxi fares.


10.Key Findings:
The analysis helps understand how different trip characteristics are associated with taxi fare.
In particular, distance travelled and trip duration can be examined to understand their relationship with the fare. The regression model provides a way to estimate the fare using the available trip information.
The exact model performance is reported in the project report and Python output.


11.Limitations:
The dataset contains only 500 observations.
The dataset includes a limited number of variables.
Factors such as traffic, weather, location, time of day, and surge pricing are not included.
The model's predictions depend on the quality and characteristics of the available data.


12.Future Scope:
The project can be improved by:
Using a larger real-world taxi dataset.
Adding pickup and drop-off locations.
Including traffic conditions.
Considering time and date information.
Comparing multiple regression algorithms.
Developing a simple web application for fare prediction.
