# Week5_Assignment
Assignment – Week 5: Introduction to Machine Learning in Data Science

# Assignment Overview
This project demonstrates the application of supervised machine learning techniques to predict house prices using Linear Regression. The Boston Housing dataset is used to build, train, and evaluate a regression model. The assignment covers data preprocessing, model training, evaluation using RMSE, cross-validation, and visualization of results.

📊 Dataset Information

Dataset Name: Boston Housing Dataset
Source: OpenML (fetched automatically using scikit-learn)
Number of instances: 506
Number of features: 13
Target variable: Median house price
Problem Type: Supervised Learning – Regression
No manual dataset download is required.

⚙️ Technologies & Libraries Used

Python
NumPy
Pandas
Matplotlib
Scikit-learn

🧠 Methodology

Load dataset using fetch_openml
Split data into training (80%) and testing (20%)
Apply feature scaling using StandardScaler
Train a Linear Regression model
Predict house prices on test data
Evaluate model using:
Root Mean Squared Error (RMSE)
5-fold Cross-Validation
Visualize results using:
Line graph for Actual Prices
Line graph for Predicted Prices

📈 Evaluation Metrics

RMSE (Root Mean Squared Error): Measures average prediction error
Cross-Validation RMSE: Measures model generalization and stability
Lower RMSE values indicate better model performance.

📉 Visualizations

Actual Prices Line Graph: Shows true house price trend
Predicted Prices Line Graph: Shows model prediction trend
Separate graphs are used to clearly compare actual values and model predictions.

✅ Results Summary

The model achieved acceptable RMSE on test data
Cross-validation RMSE was close to test RMSE
Indicates good generalization and minimal overfitting
Linear Regression performed well as a baseline model

🚀 Future Improvements

Polynomial Regression
Ridge and Lasso Regularization
Ensemble models (Random Forest, Gradient Boosting)
Feature selection techniques

▶️ How to Run the Project

Open the notebook in Jupyter or Google Colab
Run cells sequentially from top to bottom
Ensure required libraries are installed

Internet access required only for initial dataset fetch
