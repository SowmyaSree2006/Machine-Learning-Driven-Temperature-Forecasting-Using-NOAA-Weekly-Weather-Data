# Machine-Learning-Driven-Temperature-Forecasting-Using-NOAA-Weekly-Weather-Data
A machine learning project that predicts average weekly temperatures using NOAA-based weather data. The model applies Random Forest regression to analyze relationships between temperature, wind, and precipitation, demonstrating an efficient data-driven approach to weather forecasting.
# Machine Learning–Driven Temperature Forecasting

## Description
This project uses machine learning techniques to predict average weekly temperatures using NOAA-based weather data. A Random Forest regression model is trained on historical weather features such as temperature extremes, wind speed, and precipitation to generate accurate and reliable forecasts.

## Project Overview
Accurate temperature forecasting is important for fields such as agriculture, energy management, and transportation. Instead of relying on complex physical simulation models, this project demonstrates a data-driven approach using machine learning to provide efficient and high-performing temperature predictions based on real-world weather data.

## Objectives
- Preprocess and clean historical weather data
- Identify key factors influencing temperature variations
- Build a regression-based machine learning model
- Evaluate model performance using standard metrics
- Compare Random Forest and XGBoost models

## Dataset Information
- Source: CORGIS Weather Dataset (NOAA-based)
- Year: 2016
- Type: Weekly weather summaries
- Coverage: Multiple U.S. cities

### Features Used
- Average, maximum, and minimum temperature
- Precipitation
- Wind speed and wind direction
- City and state information
- Week and month details

## Tools and Technologies
- Programming Language: Python 3
- Libraries: pandas, NumPy, scikit-learn, matplotlib
- Environment: Jupyter Notebook / Google Colab

## Methodology
1. Data Preprocessing
   - Handling missing values
   - Removing duplicates
   - Normalizing numerical features
   - Extracting date-based features

2. Feature Engineering
   - Selecting relevant numerical features
   - Encoding categorical variables

3. Model Training
   - Random Forest Regressor
   - XGBoost Regressor

4. Evaluation Metrics
   - R² (Coefficient of Determination)
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)

## Results
Random Forest Regression:
- R²: 0.9989
- MAE: 0.327
- RMSE: 0.609

XGBoost:
- R²: 0.9988
- MAE: 0.405
- RMSE: 0.663

Random Forest achieved slightly better accuracy and stability.

## Key Insights
- Maximum and minimum temperatures are the most influential features
- Wind speed and seasonal factors significantly affect predictions
- Ensemble models handle non-linear weather data effectively

## Challenges Faced
- Handling missing and inconsistent data
- Managing both numerical and categorical features
- Limited data availability (only one year of data)

## Conclusion
This project demonstrates that machine learning models, particularly Random Forest regression, can effectively predict average weekly temperatures with high accuracy. The results highlight the potential of data-driven approaches to complement traditional weather forecasting methods.

## Author
Ch. Sowmya Sree  
B.Tech – Computer Science and Engineering  
SRM University AP
