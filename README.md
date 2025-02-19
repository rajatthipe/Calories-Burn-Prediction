# Calories-Burn-Prediction

This project aims to predict the number of calories burned during physical activity based on various factors. We've explored and incorporated a comprehensive set of features and employed machine learning models to achieve accurate predictions.

## Project Overview

Regular exercise is essential for maintaining a healthy lifestyle.  Accurate estimation of calorie expenditure during workouts can be a valuable tool for fitness tracking, weight management, and personalized exercise planning. This project develops a predictive model for calorie burn using machine learning techniques.

## Dataset

The dataset used in this project contains information about individuals and their physical activities.  It includes the following features:

* **Age:** Age of the individual (years).
* **Gender:** Gender of the individual (e.g., Male, Female). 
* **Height:** Height of the individual (cm or inches).
* **Weight:** Weight of the individual (kg or lbs).
* **Duration:** Duration of the physical activity (minutes).
* **Heart Rate:** Average heart rate during the activity (beats per minute).
* **Body Temperature:** Body temperature during the activity (Celsius). 
* **Activity Type:** Type of physical activity (e.g., Running, Swimming, Cycling). 
* **Calorie Burn:** The actual number of calories burned during the activity (the target variable).

## Methodology

1. **Data Preprocessing:**
    * Handling missing values.
    * Encoding categorical features (Gender, Activity Type) using one-hot encoding or label encoding as appropriate.
    * Feature scaling/normalization .

2. **Model Training:**
    * **Linear Regression:** A simple and interpretable model used as a baseline.
    * **Random Forest Regressor:** An ensemble learning method that often provides higher accuracy due to its ability to capture non-linear relationships and reduce overfitting.

3. **Model Evaluation:**
    * The performance of both models was evaluated using appropriate metrics, such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R-squared (R²), and Mean Absolute Error (MAE).

## Results

The Random Forest Regressor achieved a remarkable accuracy of **93%** (R² score) on the test set, demonstrating its effectiveness in predicting calorie burn.  The Linear Regression model provided a baseline for comparison.

## Code

The code for this project is implemented in Python and utilizes popular libraries such as:

* Pandas: For data manipulation and analysis.
* Scikit-learn: For machine learning model training and evaluation.
* NumPy: For numerical computations.
* Matplotlib/Seaborn: For data visualization.
