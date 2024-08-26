# Stock Price Prediction

# Overview
This repository contains a machine learning project developed during my internship at InternDev Pvt Ltd. The project involves predicting stock prices using various financial indicators. The model leverages Linear Regression to forecast future stock prices based on historical data.

# Project Details
# Dataset
The dataset used for this project includes stock prices and several financial indicators. The key features are:

Date: The date of the stock price record
Open: Opening price of the stock
High: Highest price of the stock on that day
Low: Lowest price of the stock on that day
Close: Closing price of the stock
Adj Close: Adjusted closing price of the stock
Volume: Number of shares traded
Company: Stock ticker symbol of the company
P/E Ratio: Price-to-Earnings ratio
Steps and Methodology
Data Preparation:

Loaded the dataset and handled missing values, especially in the Date column.
Converted Date to a numerical format and encoded categorical features such as Company.
Feature Engineering:

Transformed Date into ordinal values to use in modeling.
Encoded the Company column to numerical values for integration into the feature set.
Model Training:

Utilized Linear Regression to build and train the model on the processed data.
Evaluation:

Assessed the model performance using Mean Squared Error (MSE) and R-squared (R²) metrics.
Visualization:

Created visualizations to compare actual stock prices with predicted values.
Results
Mean Squared Error (MSE): [Insert MSE Value]
R-Squared (R²): [Insert R² Value]
The visualizations and performance metrics demonstrate the effectiveness of the model in predicting stock prices.

# Requirements
To run this project, you need the following Python libraries:

pandas
numpy
scikit-learn
matplotlib
seaborn
You can install the required libraries using pip:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib seaborn
How to Run
Clone this repository:

bash
Copy code
git clone [GitHub Repository URL]
cd [Repository Name]
Place your dataset CSV file in the project directory.

Modify the file_path variable in the script to point to your dataset file.

# Run the script:

bash
Copy code
python stock_price_prediction.py
License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
Special thanks to my team at InternDev Pvt Ltd for their guidance and support throughout this project.

Feel free to explore and contribute to the project. For any questions or feedback, please open an issue or contact me directly.
