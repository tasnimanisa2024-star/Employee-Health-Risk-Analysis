# Employee Health Risk Prediction using Machine Learning

Overview

This project presents a Machine Learning-based framework for predicting employee health risks in industrial workplaces. The study focuses on identifying critical factors such as workload, stress, fatigue, and environmental conditions that influence employee well-being and productivity.

The proposed system aims to support data-driven decision-making by integrating predictive analytics into workplace management practices.

---

Objectives

- To develop predictive models for employee health risk classification
- To identify key factors affecting employee health
- To compare the performance of multiple machine learning algorithms
- To provide insights for improving workplace health management systems

---

Dataset Description

The dataset consists of 1000 records with 17 features categorized as follows:

Demographic Features
- Age
- Gender

Job-related Features
- Job Role
- Work Experience

Workload Features
- Working Hours
- Overtime Hours
- Workload Level

Psychological Features
- Stress Level
- Anxiety Level
- Job Satisfaction

Behavioral Features
- Sleep Duration
- Physical Activity
- Break Frequency

Health Indicator
- Fatigue Level

Environmental Features
- Noise Level
- Temperature
- Safety Condition

Target Variable
- Health Risk (Binary: Low / High)

---

Data Preprocessing

The following preprocessing steps were applied:

- Handling missing values using median and mode imputation
- Encoding categorical variables using One-Hot Encoding
- Transforming the target variable into binary format
- Feature scaling using StandardScaler
- Splitting the dataset into training and testing sets (80:20)

---

Machine Learning Models

The following models were implemented and evaluated:

- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost Classifier

---

Evaluation Metrics

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve and AUC Score

---

Results

The comparative analysis of models indicates that:

- Random Forest achieved the best overall performance based on F1-score and recall
- XGBoost also demonstrated competitive performance
- Decision Tree showed relatively lower generalization capability

The higher recall value of the Random Forest model indicates its effectiveness in identifying high-risk employees, which is critical in workplace health monitoring.

---
Feature Importance Analysis

Feature importance analysis across multiple models revealed that the following factors have the greatest impact on employee health risk:

- Stress Level
- Temperature
- Fatigue Level
- Noise

These findings highlight the importance of managing workload and psychological stress in industrial environments.

---
Visualizations

The project includes:

- Distribution analysis of categorical and numerical features
- Correlation heatmap for feature relationships
- Confusion matrix comparison across models
- ROC curve analysis
- Feature importance visualization

---

Tools and Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Google Colab

---

Conclusion

This study demonstrates that machine learning models can effectively predict employee health risks using workplace-related features. The findings provide valuable insights for organizations to take preventive measures and improve employee well-being.

---

Future Work

- Integration with Management Information Systems (MIS)
- Incorporation of real-time and longitudinal data
- Exploration of deep learning models (e.g., LSTM, Neural Networks)
- Inclusion of medical and absenteeism data

---

Author

Tasnim Islam Anisa  
Undergraduate Thesis Project  
Department of Management Information Syatems (MIS)  
Noakhali Science & Technology University (NSTU)

---

Disclaimer

This project is developed for academic purposes only. The dataset used is anonymized and does not contain any personally identifiable information.

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Google Colab

---

