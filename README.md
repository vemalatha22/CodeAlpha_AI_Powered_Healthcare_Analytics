# CodeAlpha_AI_Powered_Healthcare_Analytics

## AI-Powered Healthcare Analytics for Heart Disease Prediction

### Developed as part of the Code Alpha Machine Learning Internship

---

## Project Overview

This project focuses on predicting the possibility of heart disease using Machine Learning techniques on structured medical data. Multiple classification algorithms were implemented and evaluated to analyze model performance and identify the most effective prediction model.

The project demonstrates the application of Machine Learning in healthcare analytics for assisting in early disease risk detection and supporting data-driven medical decision-making.

---

## Objectives

* Analyze healthcare data using Machine Learning techniques
* Predict heart disease risk based on patient medical attributes
* Compare multiple classification algorithms
* Evaluate models using advanced performance metrics
* Identify important healthcare features influencing predictions

---

## Dataset Information

The dataset used in this project contains patient medical information such as:

* Age
* Sex
* Chest Pain Type
* Cholesterol Level
* Blood Pressure
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression (Oldpeak)
* Number of Major Vessels
* Thalassemia

Target Variable:

* Presence or absence of heart disease

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

---

## Machine Learning Models Implemented

The following classification algorithms were implemented and compared:

1. Logistic Regression
2. Support Vector Machine (SVM)
3. Random Forest Classifier
4. XGBoost Classifier

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Train-Test Split
6. Feature Scaling
7. Model Training
8. Model Evaluation
9. Cross Validation
10. ROC-AUC Analysis
11. Feature Importance Analysis
12. Healthcare Insights and Conclusion

---

## Evaluation Metrics Used

The models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Curve
* Cross Validation Accuracy

---

## Model Performance Summary

| Model                        | Accuracy |
| ---------------------------- | -------- |
| Logistic Regression          | 87.8%    |
| Support Vector Machine (SVM) | 89.2%    |
| Random Forest                | 88.3%    |
| XGBoost                      | 87.8%    |

### Best Performing Model

Support Vector Machine (SVM) achieved the highest overall performance with strong accuracy and balanced evaluation metrics.

---

## Key Insights

* Chest pain type, oldpeak, and maximum heart rate were among the most influential features in predicting heart disease.
* Ensemble models such as Random Forest and XGBoost demonstrated strong predictive capabilities.
* Machine Learning models can effectively assist in early disease risk assessment and healthcare analytics.

---


## How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/CodeAlpha_AI_Powered_Healthcare_Analytics.git
```

2. Install required libraries

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run all notebook cells

---

## Future Improvements

* Deploy as a real-time web application
* Integrate Explainable AI (XAI)
* Train on larger healthcare datasets
* Add deep learning models for comparison
* Build a healthcare dashboard interface

---

## Author

### Vemalatha Bhimireddy

Machine Learning Intern at Code Alpha
