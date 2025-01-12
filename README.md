# Airbnb Listing Price Prediction in London

This repository contains the code and resources for my project, where I predict the listing prices of Airbnb properties in London by leveraging both **textual** and **tabular data**. The goal of this project was to develop a robust machine learning pipeline capable of accurately estimating prices using advanced models and a stacked ensemble approach.

## Project Overview

The project follows a structured approach:

1. **Exploratory Data Analysis (EDA):**  
   A thorough examination of the dataset to identify features with strong predictive power and understand patterns in the data.  

2. **Data Cleaning and Preprocessing:**  
   Includes handling missing values, encoding categorical variables, and preparing text and tabular features for modeling.  

3. **Model Building and Evaluation:**  
   Various models were tested and evaluated to identify the best-performing ones:

   **For Tabular Data:**  
   - Linear Regression  
   - Random Forest  
   - XGBoost  
   - Deep Neural Network  

   **For Text Data:**  
   - LSTM  
   - GRU  
   - Bidirectional GRU  
   - BERT  

4. **Stacked Ensemble Model:**  
   The final solution employs a stacked ensemble consisting of:  
   - **XGBoost** for tabular data.  
   - **BERT** for textual data.  
   - A **DNN** to merge the predictions from XGBoost and BERT into a final output.
