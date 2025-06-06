# Midterm Project – Financial Data Analytics (Spring 2025)

This folder contains the submission materials for the **Midterm Kaggle Competition** of the Financial Data Analytics course. The objective was to **predict customer overstress** using a given labeled dataset and blind test set on Kaggle.

 **Competition Link**: [Kaggle Competition](https://www.kaggle.com/competitions/financial-data-analytics)

---

##  Project Summary

- **Student Name**: Mohammad Tayyab Alam  
- **Roll Number**: 24157  
- **Kaggle Leaderboard Position**: **7th**
- **Best Model**: XGBoost with score **0.95338**

The project explored **11 different models** using techniques like:
- Feature engineering (sum features, normalization)
- Outlier handling
- Imputation of missing values
- Stratified cross-validation
- Extensive hyperparameter tuning

---

##  Files Included

| File | Description |
|------|-------------|
| [`24157_Mohammad_Tayyab_Alam_Midterm_KAGGLE.ipynb`](https://github.com/tayyabalam77/course-progress/blob/main/Midterm_Kaggle_Project/24157_Mohammad_Tayyab_Alam_Midterm_KAGGLE%20.ipynb) | Jupyter Notebook with full analysis and modeling |
| [`24157_Mohammad_Tayyab_Alam_Midterm_KAGGLE.html`](https://github.com/tayyabalam77/course-progress/blob/main/Midterm_Kaggle_Project/24157_Mohammad_Tayyab_Alam_Midterm_KAGGLE%20.html) | Rendered HTML version of notebook |
| [`24157_Mohammad_Tayyab_Alam_MIDTERM_KAGGLE.pdf`](https://github.com/tayyabalam77/course-progress/blob/main/Midterm_Kaggle_Project/24157_Mohammad_Tayyab_Alam_MIDTERM_KAGGLE%20.pdf) | Final PDF presentation |
| [`FDA KAGGLE SUMMARY.docx`](https://github.com/tayyabalam77/course-progress/blob/main/Midterm_Kaggle_Project/FDA%20KAGGLE%20SUMMARY.docx) | One-page project summary |
| [`Financial Data Analytics_ Spring 2025.pdf`](https://github.com/tayyabalam77/course-progress/blob/main/Midterm_Kaggle_Project/Financial%20Data%20Analytics_%20Spring%202025%20.pdf) | Midterm Question Paper |

**Note** : The data sets can be found on the Kaggle Competition Link.
---

##  Key Findings

- **XGBoost** emerged as the best model after extensive tuning, achieving a score of **0.95338**.
- **Random Forest**, **LightGBM**, and **CatBoost** were close contenders.
- Models like **Naive Bayes**, **KNN**, **Decision Tree**, and **Logistic Regression** were discarded due to poor scalability or low AUC scores.
- Class imbalance was mitigated via **scale_pos_weight** and class weighting strategies.
- Techniques like **stacking** were explored but did not outperform XGBoost.
- Emphasis was placed on computational efficiency and performance balance across over 70 submissions.

---

##  Notes

This project demonstrated deep exploration and competitive modeling under a real-world scenario with leaderboard pressure. It helped strengthen practical skills in:
- Model comparison
- Feature importance
- Evaluation metrics (AUC)
- Kaggle best practices

