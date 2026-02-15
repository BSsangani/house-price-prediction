# House Price Prediction using Machine Learning

## Description
In this project, I built a machine learning model to predict house prices using the California Housing dataset, which contains **20,640 houses** with **8 features** such as median income, average rooms, and house age. I experimented with both **Linear Regression** and **Random Forest Regression** models to see which predicts more accurately.  

The project also includes **graphs and visualizations** to understand data patterns, correlations, feature importance, and the accuracy of predictions.  

## Features
- Data Preprocessing (scaling and splitting)
- Model Training (Linear Regression & Random Forest Regression)
- Model Evaluation (R² Score, RMSE)
- Graphical Insights:
  - Correlation heatmap  
  - Predicted vs Actual prices  
  - Price distribution  
  - Feature importance  
  - Pairplots of key features
- Predicting new house prices  

## Model Performance
- **Linear Regression:** R² = 0.61, RMSE = 0.82  
- **Random Forest Regression:** R² = 0.81, RMSE = 0.56  

Random Forest performed better, capturing complex relationships in the data.  

## Example Prediction
Using the trained Random Forest model, I predicted the price of a new house and got a value of **$265,000**.  

## Key Insights
1. Median income (MedInc) is the strongest factor affecting house prices.  
2. More rooms and newer houses tend to have higher prices.  
3. Most houses in the dataset are below **$200,000**.  
4. Random Forest predictions closely match actual prices, making it reliable for real-world use.  

## Requirements
- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  

Install dependencies using:  
```bash
pip install -r requirements.txt
