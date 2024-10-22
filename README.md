# Data Analytics and Visualization Bootcamp 
## University of Toronto
### Group 1
### Date: October 15, 2024
### Project 4 - Real Estate Price Prediction with Machine Learning
### Group Members: Gabriela, Janhavi, Santiago, Miguel, Thet


## Overview of the analysis: 
 - The purpose of this project is to develope a deep learning model to help explore real estate housing price prediction in Illinois, USA based on selected features.

## Data Preprocessing
 - A CSV file containing the dataset of more than 1,000,000 real estate listings in the US broken by State and Zip Code was used. The data was retrieved from Kaggle.

#### Target Variable
 - price (Housing price, it is either the current listing price or recently sold price if the house is sold recently)

#### Feature Variables
 - brokered by (categorically encoded agency/broker)
 - status (Housing status - a. ready for sale or b. ready to build)
  - bed (# of beds)
 - bath (# of bathrooms)
 - acre_lot (Property / Land size in acres)
 - street (categorically encoded street address)
 - city (city name)
 - state (state name)
 - zip_code (postal code of the area)
 - house_size (house area/size/living space in square feet)
 - prev_sold_date (Previously sold date)
 - Preprocessing steps included handling missing values, categorical encoding, and scaling numerical features.

## Compiling, Training, and Evaluating the Model
 - Various states were considered and we decided on Illinois. Real estate listings and sold prices within the cities of Illinois were used in the training of the data.
 - Data was processed and cleaned by removing NULL/NaN values from essential columns.

### Model Performance
  - 77% Accuracy attained
  
### Steps Taken to increase model performance
- Hyperparameter tuning
- Adding dropout layers to prevent overfitting
- Experimenting with different architectures and optimization techniques

## Tableau
This project provides a comprehensive analysis of real estate pricing trends, visualized through Tableau. The dashboard explores factors such as house size, lot size, and location, offering interactive insights into the real estate market. [View the Tableau dashboard here](https://public.tableau.com/app/profile/janhavi.bharati/viz/Project4_17290938313380/Dashboard1)
  
## Summary
Our model predicts housing prices in Illinois with an accuracy of 77%. Further improvements can be made by refining features, exploring different models, and continuing to optimize hyperparameters.

## User Interface
![Screenshot 2024-10-15 at 4 48 00 PM](https://github.com/user-attachments/assets/d66fdef2-6498-4d42-8cc1-af075f5e1b23)

