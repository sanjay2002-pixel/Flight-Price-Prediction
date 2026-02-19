#  Flight Price Prediction using Machine Learning

##  Problem Statement

Airline ticket prices fluctuate dynamically based on multiple factors such as airline, journey date, duration, and number of stops.

The objective of this project is to build a **machine learning regression model** that accurately predicts flight prices using historical booking data.

###  Business Impact

This solution can help:

- Customers identify optimal booking times  
- Travel companies forecast pricing trends  
- Airlines analyze demand patterns  



##  Dataset Overview

The dataset contains the following features:

- Airline  
- Source  
- Destination  
- Journey Date  
- Duration  
- Total Stops  
- Additional Information  
- **Price (Target Variable)**  



##  Project Workflow

### 1️⃣ Data Cleaning
- Removed null values  
- Converted date-time features into structured format  
- Extracted journey day and month  

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed price trends by airline  
- Studied the impact of total stops and duration  
- Identified and handled outliers  

### 3️⃣ Feature Engineering
- Applied one-hot encoding for categorical variables  
- Extracted time-based features  
- Removed multicollinearity  

### 4️⃣ Model Building

Models implemented:

- Linear Regression  
- Random Forest Regressor  

### 5️⃣ Model Evaluation

Evaluation metrics used:

- R² Score  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  

Random Forest performed better due to its ability to capture non-linear relationships in the dataset.



## 📈 Key Insights

- Flights with more stops tend to be cheaper  
- Duration significantly impacts ticket price  
- Airline choice strongly influences pricing  



## 🧰 Tech Stack

- Python  
- Pandas  
- NumPy  
