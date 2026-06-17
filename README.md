# Level-3-Project-1-Predictive-Modeling-Classification-
Build and evaluate a classification model to predict categorical outcomes (e.g., predict if a customer will churn)
Customer Churn Prediction Using Machine Learning

## Project Overview

This project was completed as part of the Codveda Technologies Data Analysis Internship – Level 3 (Advanced).

The objective of this project was to build and evaluate machine learning classification models capable of predicting customer churn. Multiple classification algorithms were trained, evaluated, and optimised to determine the most effective approach for identifying customers likely to discontinue service.

---

## Business Problem

Customer churn is a critical challenge for service-based organisations. Acquiring new customers is often more expensive than retaining existing ones. Therefore, accurately predicting customer churn enables businesses to implement proactive retention strategies and reduce revenue loss.

This project aims to leverage machine learning techniques to identify customers with a high likelihood of churning based on historical customer behavior and usage patterns.

---

## Objectives

- Preprocess customer data
- Handle categorical variables
- Perform feature scaling
- Train multiple classification models
- Evaluate model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- Perform hyperparameter tuning using Grid Search
- Identify key churn drivers
- Visualise model performance

---

## Dataset Information

The dataset contains telecommunications customer information including:

- State
- Account Length
- Area Code
- International Plan
- Voice Mail Plan
- Number of Voice Messages
- Total Day Minutes
- Total Day Calls
- Total Day Charges
- Total Evening Minutes
- Total Evening Calls
- Total Evening Charges
- Total Night Minutes
- Total Night Calls
- Total Night Charges
- Total International Minutes
- Total International Calls
- Total International Charges
- Customer Service Calls
- Churn (Target Variable)

---

## Tools and Technologies

- Python
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab

---

## Machine Learning Models

### Logistic Regression

A baseline classification model used to establish initial performance benchmarks.

### Decision Tree Classifier

A tree-based classification model capable of capturing non-linear relationships.

### Random Forest Classifier

An ensemble learning model that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Model Performance

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 84% |
| Decision Tree | 90% |
| Random Forest | 95% |

### Best Model

🏆 Random Forest Classifier

The Random Forest model achieved the highest overall predictive performance and was selected as the final model.

---

## Hyperparameter Tuning

GridSearchCV was used to optimize Random Forest parameters including:

- Number of Trees (n_estimators)
- Maximum Tree Depth (max_depth)
- Minimum Samples Split (min_samples_split)

This improved model performance and generalization capability.

---

## Visualizations

### Model Accuracy Comparison

![Model Accuracy Comparison](images/Model_Comparison.png)

### Confusion Matrix

![Confusion Matrix](images/Confusion_Matrix.png)

### Feature Importance

![Feature Importance](images/Feature_Importance.png)

---

## Key Findings

- Random Forest outperformed all other classification models.
- Total Day Minutes was the most influential predictor of churn.
- Customer Service Calls significantly impacted churn likelihood.
- Customers subscribed to International Plans exhibited higher churn risk.
- Customer usage behavior strongly influenced churn predictions.

---

## Business Impact

The developed model can assist organizations in:

- Identifying high-risk customers
- Improving customer retention initiatives
- Reducing revenue loss from churn
- Supporting data-driven customer engagement strategies

---

## Skills Demonstrated

- Data Preprocessing
- Feature Engineering
- Feature Scaling
- Classification Modeling
- Hyperparameter Tuning
- Model Evaluation
- Machine Learning
- Data Visualization
- Business Insight Generation

---

## Conclusion

This project successfully applied machine learning techniques to predict customer churn. Random Forest achieved the best overall performance with approximately 95% accuracy and demonstrated strong capability in identifying customers at risk of leaving. The project highlights the effectiveness of predictive analytics in improving customer retention and supporting strategic business decisions.

---

## Author

Adeyemi Victor

Data Analyst | Python | SQL | Power BI | Excel
Completed as part of the Codveda Technologies Data Analysis Internship Program.
