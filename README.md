# CMPE-255-Data-Science-Chatbot-mode

# **Used Car Price Prediction - Kaggle Competition**

Welcome to my **Used Car Price Prediction** project! This repository contains all the code and resources I used to participate in a Kaggle competition focused on predicting the price of used cars based on various attributes such as age, mileage, and brand.

🎉 **Exciting News!** I completed this Kaggle competition in record time with the help of **ChatGPT**. You can read all about my experience in my [Medium article](https://medium.com/@rushabh22runwal/how-i-completed-a-kaggle-competition-in-minutes-using-chatgpt-4o-8fe37b9a836b), where I break down how ChatGPT guided me through the entire process.

## 📜 **Overview of the Project**

The goal of this competition was to build a machine learning model capable of predicting the price of used cars. The dataset contains features such as:

- **Name**: The name of the car
- **Year**: Year of manufacture
- **Kilometers_Driven**: The total distance driven by the car
- **Fuel_Type**: Type of fuel used (Petrol, Diesel, CNG, etc.)
- **Transmission**: Whether the car has manual or automatic transmission
- **Owner_Type**: Number of previous owners
- **Mileage**, **Engine**, **Power**, **Seats**: Various specifications of the car

The target variable for this task is the **Price** of the car, and the model was evaluated using **Root Mean Squared Error (RMSE)**.

### 🚀 **Key Steps in the Workflow:**
1. **Data Understanding**: Loaded the dataset and identified missing values, data types, and overall structure.
2. **Data Cleaning & Feature Engineering**: Handled missing data, engineered features like **Car_Age** and **Brand**, and converted categorical variables to numerical using one-hot encoding.
3. **Modeling**: Trained multiple models, including:
   - Linear Regression
   - Decision Tree
   - Random Forest (Best Performing)
   - Gradient Boosting
4. **Evaluation**: Used RMSE to evaluate model performance, with **Random Forest** yielding the best results.
5. **Submission**: Generated predictions for the test set and prepared the submission file.
