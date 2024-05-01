# LGBM Solution to AMEX Default Prediction Kaggle Competition

This GitHub repository contains our code for the American Express Default Prediction competition. Developped in collaboration with Ben See Jian Rong and Younes Siyar, our team utilized LightGBM, an advanced machine learning technique, to predict credit card defaults. This solution highlights our strategic approach to handle a massive dataset with a complex structure, focusing on efficiency and scalability to meet the challenges posed by real-world financial data.
  
## Table of Contents
1. [Competition Description](#competition-description)
2. [Challenges of the Problem](#challenges-of-the-problem)
3. [Proposed Solution](#proposed-solution)
4. [Solution Effectiveness](#solution-effectiveness)
5. [Conclusion](#conclusion)

## Competition Description
The competition, hosted by American Express, focused on using machine learning to predict credit default. The challenge involved handling an industrial-scale dataset with complex features including delinquency, spend, payment, balance, and risk variables.

## Challenges of the Problem
Key challenges included managing the large dataset size, addressing data quality issues, and the intensive computational requirements.

## Proposed Solution
Our approach utilized LightGBM due to its efficiency and scalability. Initial experiments with Random Forest provided insights but were not scalable for the competition's dataset. We opted for LightGBM, a gradient boosting framework that uses tree-based learning algorithms, known for its superior handling of large datasets.

#### Key Steps in Our LightGBM Solution:
- **Data Preprocessing:** To handle the vast amounts of data, we employed techniques such as handling missing values, encoding categorical variables, and reducing dimensionality where feasible.
- **Feature Engineering:** We crafted features that could capture nuances in the data, significantly impacting the model's predictive power.
- **Model Configuration:** Tuning LightGBM parameters like learning rate was crucial to optimize our model for accuracy and efficiency.
- **Validation Strategy:** To ensure the robustness of our model, we implemented a cross-validation strategy, which helped in identifying stable and reliable model configurations.

## Solution Effectiveness 
Extensive data preprocessing and hyperparameter tuning led to significant improvements:
- **AUC:** 0.97966
- **Binary Log Loss:** 0.167891
- **AMEX Score:** 0.78410

## Conclusion
This project provided a profound learning experience in handling real-world data and emphasized the importance of model selection, data quality, preprocessing, and collaborative teamwork.
