# NVIDIA Stock Price Prediction Project

This project explores NVIDIA's stock price data using exploratory data analysis, visualization, and machine learning models. It was developed as part of a data science experiment to understand financial time series patterns and apply predictive modeling techniques.

Case Study of the experiment: https://animated-talos-5ae.notion.site/Nvidia-Stock-Prediction-Experiment-1bb1204ea4d681838b93ca457c91c1ed

## 📊 Dataset
- Source: [Kaggle - NVIDIA Stock Data](https://www.kaggle.com/datasets/muhammaddawood42/nvidia-stock-data)  
- Columns: `Date, Adj Close, Close, High, Low, Open, Volume`  
- Time range: Historical NVIDIA stock prices  

## 🔎 Key Steps
1. **Data Preprocessing**
   - Converted date fields to datetime format
   - Extracted time-based features (Year, Month, Day of Week, etc.)
   - Handled missing values
   - Created moving averages (SMA, EMA) and interaction features  

2. **Exploratory Data Analysis**
   - Price vs. trading volume visualization
   - 50-day and 200-day moving averages
   - Histogram of daily returns

3. **Modeling**
   - Random Forest Regressor for predicting adjusted close prices
   - Evaluation metrics:
     - Mean Squared Error (MSE)
     - R-squared (R²)
   - Feature importance analysis  

## ⚙️ Tech Stack
- **Python**: pandas, numpy, matplotlib, seaborn  
- **Machine Learning**: scikit-learn (Linear Regression, Random Forest)  

## 📈 Results
- The Random Forest model achieved reasonable predictive performance.  
- Feature importance analysis showed which temporal and volume-related factors contributed most to price predictions.  
