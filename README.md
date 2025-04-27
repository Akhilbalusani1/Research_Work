# Research_Work

## Overview
This repository contains the implementation of my research project titled **"Unleashing XGBoost: The Ultimate Predictor in Supply Chain Demand Forecasting."**  
The project focuses on improving retail sales forecasting accuracy by experimenting with various machine learning and deep learning models, especially XGBoost and a hybrid CNN-LSTM-XGBoost model.

## Models Implemented
- XGBoost
- CNN-LSTM-XGBoost Hybrid
- Linear Regression
- Decision Tree
- Random Forest
- ARIMA
- LSTM
- CNN
- Stacked Ensemble Models

## Dataset
The dataset used in this project is based on a public retail sales dataset from Kaggle.  
I enriched it further by adding:
- Weather data
- Sentiment scores
- Lag features
- Temporal features like month, day of the week, and holiday indicators

## Evaluation Metrics
The models are evaluated using the following metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

XGBoost achieved the best performance with an R² score of **0.9533**.

## Project Structure
```
Research_Work/
│
├── data/                # Raw and processed datasets
├── models/              # Scripts for training different models
├── results/             # Evaluation results and plots
├── notebooks/           # Jupyter notebooks for experiments
├── README.md            # Project documentation
└── requirements.txt     # Python dependencies
```

## Future Work
- Moving from univariate to multivariate forecasting
- Exploring Transformer-based models for time series
- Using AutoML for better model tuning
- Deploying the models for real-time predictions

## How to Run
1. Clone the repository:
    ```
    git clone https://github.com/Akhilbalusani1/Research_Work.git
    cd Research_Work
    ```

2. Install the required Python packages:
    ```
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebooks:
    ```
    jupyter notebook
    ```

## Acknowledgements
- [Retail Sales Dataset by Kaggle](https://www.kaggle.com/datasets/kirbysasuke/retail-sales) for providing the base dataset
- Jupyter Notebook for providing an interactive environment for model experimentation
- Libraries like scikit-learn, xgboost, keras, and statsmodels for model development
