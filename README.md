# Predicting the Impact of Road Accidents on Traffic Flow

This project focuses on enhancing urban transportation management by predicting the impact of traffic accidents on traffic flow. Utilizing advanced machine learning techniques, our goal is to develop a model capable of forecasting real-time traffic disruptions, ultimately improving road safety and minimizing congestion.

## Dataset
The primary dataset used is the [US Accidents Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) from Kaggle, covering traffic accidents across 49 US states from February 2016 to March 2023. This dataset includes approximately 7.7 million records with 46 distinct features related to accident severity, weather conditions, geographical locations, and more.

## Methods and Models
We explored various machine learning models to address the challenges posed by large and complex data, noise, and real-time changes in conditions. The models include:
- Linear Models (Logistic Regression, SGD)
- K-Nearest Neighbors (KNN)
- Decision Trees
- Ensemble Methods (Random Forest, XGBoost, LightGBM, CatBoost)
- Imbalanced Learning Techniques (Self-Paced Ensemble, Balanced Bagging)
- Deep Neural Networks with regularization techniques like Batch Normalization and Dropout
- A final Voting ensemble combining the best models

## Results
Our best model, a Voting ensemble combining predictions from Random Forest, XGBoost, LightGBM, SPE, and Balanced Bagging, achieved an accuracy of 90% and a macro-average F1-score of 0.70.

## Conclusion and Future Work
The project successfully demonstrated the use of machine learning to predict traffic disruptions caused by road accidents. Future work could involve integrating geospatial or time-series data, refining models to better handle class imbalance, and developing a real-time accident risk prediction framework.


