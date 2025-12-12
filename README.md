**Predicting IBM Employee Attrition Using Machine Learning**
This project applies machine learning techniques to analyze and predict employee attrition using the IBM HR Analytics Employee Attrition dataset. The goal is to help HR teams identify key factors that drive turnover and build a predictive model that can flag employees at risk of leaving.

**The project includes:**

Exploratory Data Analysis (EDA) to understand demographic, job-related, and satisfaction patterns.

Data preprocessing, including one-hot encoding, feature scaling, and multicollinearity reduction.

Handling class imbalance using SMOTE to improve minority class prediction.

Model development and comparison using Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, SVM, and Neural Networks.

Hyperparameter tuning with GridSearchCV to optimize model performance.

Evaluation using accuracy, recall, precision, F1-score, ROC-AUC, and confusion matrices.

Feature importance analysis to identify the strongest drivers of attrition.

**🔍 Key Insights**

Overtime, job role, and employee satisfaction significantly influence attrition.

Logistic Regression emerged as the best-performing model with strong recall and interpretability, making it well-suited for HR decision-making.

Gradient Boosting and Neural Networks performed competitively but lacked interpretability or recall compared to Logistic Regression.

**🧠 Techniques Used**

Python, Pandas, NumPy, Scikit-Learn

SMOTE (Synthetic Minority Oversampling Technique)

GridSearchCV for model tuning

ROC Curves & Feature Importance Visualization

Machine Learning Classification Models

**🎯 Objective**

To build an accurate and interpretable attrition prediction model that supports data-driven HR strategies, improves employee retention, and reduces turnover costs.
