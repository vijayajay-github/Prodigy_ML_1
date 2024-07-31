# House Price Prediction using Linear Regression
# Project Overview
This project aims to predict house prices using a linear regression model. The dataset used contains various features related to houses, and the target variable is the median_house_value. The project includes data preprocessing, feature engineering, model training, and evaluation.

Dataset
The dataset used in this project is derived from a housing dataset, which includes features such as longitude, latitude, total_rooms, total_bedrooms, population, households, and the target variable median_house_value.

# Project Structure
├── housing.csv                 # Dataset file
├── house_price_prediction.py   # Main script for data preprocessing, model training, and evaluation
├── README.md                   # Project documentation
└── requirements.txt            # List of required packages

pandas is used for data manipulation and analysis
numpy is a fundamental package for numerical computing in Python
matplotlib is a plotting library for creating static, interactive, and animated visualizations
seaborn is a statistical data visualization library based on Matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics
scikit-learn is a machine learning library in Python that provides simple and efficient tools for data mining and data analysis

# Model Training
A linear regression model is trained using the preprocessed data. The model is trained to predict the median_house_value based on features such as longitude, latitude, total_bedrooms, and total_rooms.

# Results
R² Score: The R² score of the model on the test set is obtained and displayed.
Visualization: A scatter plot is generated to visualize the actual vs. predicted house prices.
# Conclusion
This project demonstrates the process of building a linear regression model for house price prediction. The model's performance can be further improved by incorporating more sophisticated feature engineering and trying different machine learning algorithms.
