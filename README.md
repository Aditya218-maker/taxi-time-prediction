# taxi-time-prediction
# 🚕 Taxi Trip Duration Prediction

This project focuses on predicting taxi trip durations using various machine learning models. Accurate trip time predictions are crucial for improving customer satisfaction, optimizing route planning, and enhancing operational efficiency in transportation services.

## 📁 Project Structure

- **Exploratory Data Analysis (EDA)**: Initial data exploration, cleaning, and visualization.
- **Feature Engineering**: Transformation of raw data into meaningful input features.
- **Model Building**: Implemented and compared:
  - Linear Regression
  - Decision Tree Regressor
  - K-Nearest Neighbors (KNN) Regressor
- **Evaluation Metrics**: Assessed models using:
  - RMSE (Root Mean Squared Error)
  - R² Score
- **Final Model Selection**: Chose KNN as the best-performing model based on evaluation metrics.

 🎯 Objectives

- Predict trip durations based on pickup and dropoff locations, distance, and other ride features.
- Compare multiple regression models to find the most accurate and reliable one.
- Deploy a model that could enhance ETA predictions for real-world applications.

## 📊 Evaluation Summary

| Model            | RMSE ↓   | R² Score ↑ |
|------------------|----------|------------|
| Linear Regression | High     | Low        |
| Decision Tree     | Moderate | ~0.55      |
| KNN Regressor     | **Low**  | **0.72**   |

✅ **KNN was selected as the final model** due to its lowest RMSE and highest R² score.

 📌 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab
