# 🚦 Big Data for Road Safety: Collision Severity Prediction
A complete end-to-end machine learning project focused on predicting the severity of road traffic collisions using the UK Department for Transport’s 2023 collision dataset.

The project includes group analysis and individual model development (LightGBM, Random Forest, etc.) with feature engineering, SMOTE balancing, and hyperparameter tuning.

Developed as part of the Big Data for Decision Making module at Aston University by Glawin Alva.

---

## 📂 Repository Structure

big-data-road-safety-prediction/  
├── README.md  
├── datasets/  
│   ├── dft-road-casualty-statistics-collision-provisional.csv  
│   ├── trainset_road-casualty-statistics-collision.xlsx  
│   ├── testset_road-casualty-statistics-collision.xlsx  
│   ├── X_train.csv  
│   ├── y_train_encoded.csv  
│   ├── X_test.csv  
│   └── y_test.csv  
├── notebooks/  
│   ├── group_project_analysis.ipynb  
│   └── individual_risk_prediction_glawin.ipynb  
├── reports/  
│   ├── group/  
│   │   └── Big_data_for_decision_making_GROUP_FINAL.pdf  
│   └── individual/  
│       └── BIG_data_Indivisual_Assignment_Candidate_no_784750.pdf   
└── environment/  
    └── requirements.txt  

---

## 👥 Group Project Overview

**Title**: Predictive Modeling for Road Traffic Collisions  
**Team Members**:
- Candidate No: 784750 *(Glawin Alva - My contribution)*
- Candidate No: 393886
- Candidate No: 379642
- Candidate No: 413087

**Objective**:  
Develop a predictive model that identifies high-risk areas, conditions, and contributing factors for road collisions using big data analytics and machine learning models.

### 🔍 Techniques Used
- Exploratory Data Analysis (EDA)
- Data Preprocessing and Cleaning
- Feature Engineering
- Outlier Detection (IQR method)
- Machine Learning Modeling

---

## 🙋‍♂️ Individual Contribution

**Focus Area**: Predicting the Risk of Severe Collisions for Insurance Premium Adjustments

**My Candidate No**: 784750 | **Name**: Glawin Alva

**Goal**:  
Build and evaluate predictive models to classify the severity of road traffic collisions to help insurance companies optimize premium pricing.

### 🛠️ Tools & Techniques Used
- Python, Pandas, NumPy, Scikit-learn
- Feature Engineering: Temporal, Spatial, Environmental factors
- Class Balancing: SMOTE (Synthetic Minority Oversampling Technique)
- Machine Learning Models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - LightGBM *(best performance)*
  - CatBoost
- Model Evaluation Metrics: Accuracy, Precision, Recall, F1-Score
- Hyperparameter Tuning: GridSearchCV

### 🏆 Best Model
**LightGBM Classifier**
- Accuracy: 82%
- Precision: 77%
- Recall: 82%
- F1 Score: 79%

---

## 📜 Reports

- [Group Final Report](reports/group/Big_data_for_decision_making_GROUP_FINAL.pdf)
- [Individual Report](reports/individual/BIG_data_Indivisual_Assignment_Candidate_no_784750.pdf)

---

## 📌 Important Notes
- The group project and individual assignment are completed for educational purposes under Aston University's Big Data coursework.
- All datasets used are publicly available (DfT Road Casualty Statistics 2023).
- All team members are properly credited.
- All modeling in `/individual/` and `/notebooks/individual_risk_prediction_glawin.ipynb` reflects my original work.

---

## 📫 Contact

**Glawin Alva**  
AI-Focused Data Engineer | Driving Data-Driven Business Transformation  
📍 Birmingham, United Kingdom  
📧 glawin24@gmail.com  
📞 +44 7341 704465  
🔗 [LinkedIn Profile](https://linkedin.com/in/glawin-alva-gg)  
🐙 [GitHub Profile](https://github.com/GlawinAlva24)

---

