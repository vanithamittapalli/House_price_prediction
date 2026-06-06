# House_price_prediction
House Price Prediction Using Machine Learning
Project Overview
This project builds a Machine Learning Regression Model to predict house prices using the California Housing Dataset. The workflow includes data loading, feature selection, model training, prediction, and performance evaluation.
Objective
To predict housing prices based on various housing features and evaluate the model's prediction accuracy.
Dataset
The project uses the California Housing Dataset available in the scikit-learn library.
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Machine Learning Workflow
1. Data Loading
Load the California Housing Dataset.
Convert the data into a Pandas DataFrame.
2. Feature Selection
Use SelectKBest with f_regression.
Select the top 5 most relevant features for prediction.
3. Data Splitting
Split the dataset into:
80% Training Data
20% Testing Data
4. Model Training
Train a Linear Regression model using the selected features.
5. Prediction
Generate house price predictions on the test dataset.
6. Model Evaluation
The model is evaluated using:
R² Score (Coefficient of Determination)
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Expected Output
The notebook displays:
Dataset information
Feature scores
R² Score
MAE
RMSE
How to Run
Install the required libraries:
Bash
pip install pandas numpy scikit-learn
Run the Python notebook or script:
Bash
python house_price_prediction.py
Conclusion
This project demonstrates a complete Machine Learning pipeline for house price prediction, including feature selection, model training, prediction, and evaluation using regression techniques. The results help assess how accurately the model predicts housing prices based on the selected features.
