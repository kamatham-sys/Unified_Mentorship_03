# TCS Stock Data Analysis (Machine Learning Internship)

This project focuses on analyzing and predicting Tata Consultancy Services (TCS) stock prices using historical market data and machine learning models.

## Objectives
- Clean and preprocess historical TCS price data.
- Perform Exploratory Data Analysis (EDA) to find trends and volatility.
- Engineer lag features and moving averages as model inputs.
- Build and evaluate a Random Forest model for next-day close price prediction.

## Dataset
- `TCS_stock_history.csv`: Columns include Date, Open, High, Low, Close, Adj Close, Volume, and Dividends.
- Data preparation involves parsing dates and numeric conversions.

## Methodology
- Handle missing values, sort and structure the data.
- Feature engineering: lag features (1-5), rolling averages, day-of-week, month.
- Time-aware split (80% train, 20% test).
- Model training with RandomForestRegressor.
- Evaluation using MAE, MAPE, and R².

## Results & Insights
- Baseline performance metrics are provided; further improvement possible with more indicators and hyperparameter tuning.
- Visual trends highlight SMA20, SMA50, and daily returns.
- The model demonstrates foundational predictive capability.

## Future Work
- Hyperparameter tuning and advanced model selection.
- Integration of technical indicators (EMA, RSI, MACD).
