# PUBG Finish Placement Prediction

This project focuses on creating a predictive model to estimate the final standings of players in a PUBG game, whether playing solo or in teams. By analyzing over 65,000 anonymized game stats, we aim to leverage machine learning techniques to forecast player rankings accurately.

## Overview

- **Objective**: To predict players' ranking positions in PUBG competitions using machine learning.
- **Data Source**: Anonymized game stats from over 65,000 PUBG games, presented in three CSV files: train, test, and sample submission.

## Methodology

1. **Data Preparation**: The dataset, obtained from Kaggle, contains detailed post-game statistics for each player. It requires preprocessing to fit the needs of predictive modeling.
2. **Exploratory Data Analysis (EDA)**: Initial data exploration to understand the distributions, correlations, and patterns within the dataset.
3. **Feature Engineering**: Creation of new features that could enhance the model's predictive capabilities based on the insights from EDA.
4. **Model Selection**: Utilization of CatBoostRegressor and LGBMRegressor models, with GridSearchCV for hyperparameter tuning, aiming for optimal performance.
5. **Evaluation**: Assessment of model performance using suitable metrics, considering the ranking prediction nature of the problem.

## Insights and Conclusions

The notebook details the steps taken from data downloading, preprocessing, exploratory analysis, to model training and evaluation. It demonstrates the application of advanced machine learning techniques in predicting outcomes in a highly competitive environment. The project showcases the potential of using game statistics to forecast player performance and rankings in PUBG competitions.

---

This summary encapsulates the essence of the notebook, highlighting the project's objectives, methodology, and insights. It provides a concise overview for readers to understand the purpose and outcomes of your analysis.
