# LGBM Solution to American Express Default Prediction Kaggle Competition

### Table of Contents
1. [Specific Roles and Contributions of Group Members](#specific-roles-and-contributions-of-group-members)
2. [Performance](#performance)
3. [Competition Description](#competition-description)
4. [Challenges of the Problem](#challenges-of-the-problem)
5. [Proposed Solution](#proposed-solution)
6. [Solution Effectiveness - Experiments](#solution-effectiveness---experiments)
7. [Conclusion](#conclusion)

---

### Specific Roles and Contributions of Group Members
Each group member took on different machine learning models to tackle the task:
- **Nicolas Bolouri:** Random Forest experimentation and LightGBM model tuning.
- **Ben See Jian Rong:** Code readability and data formatting.
- **Younes Siyar:** Data exploration and preprocessing.

---

### Performance
Our final model achieved an evaluation score of 0.78410 using the formula \( M = 0.5 \cdot (G + D) \) where \( G \) is the Normalized Gini Coefficient and \( D \) is the default rate captured at 4%.

---

### Competition Description
The competition, hosted by American Express, focused on using machine learning to predict credit default. The challenge involved handling an industrial-scale dataset with complex features including delinquency, spend, payment, balance, and risk variables.

---

### Challenges of the Problem
Key challenges included managing the large dataset size, addressing data quality issues, and the intensive computational requirements.

---

### Proposed Solution
Our approach utilized LightGBM due to its efficiency and scalability. Initial experiments with Random Forest provided insights but were not scalable for the competition's dataset.

---

### Solution Effectiveness - Experiments
Extensive data preprocessing and hyperparameter tuning led to significant improvements:
- **AUC:** 0.97966
- **Binary Log Loss:** 0.167891
- **AMEX Score:** 0.78410

---

### Conclusion
This project provided a profound learning experience in handling real-world data and emphasized the importance of model selection, data quality, preprocessing, and collaborative teamwork.

---

For more details on each section, refer to the corresponding pages of the project report.
