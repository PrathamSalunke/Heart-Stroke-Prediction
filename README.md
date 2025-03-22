# Heart-Stroke-Prediction
This project leverages machine learning to predict the presence of heart disease in patients based on various health parameters. 
## Introduction
Heart disease is one of the leading causes of death worldwide. Early detection of heart disease can significantly improve patient outcomes. This project uses machine learning techniques to analyze patient data and classify whether an individual has heart disease (`1`) or not (`0`).
## Features
The dataset consists of 303 rows and 14 columns. Each row represents a patient, and the columns represent various medical attributes.
- `age`: Age of the patient.
- `sex`: Gender (1 = Male, 0 = Female).
- `cp`: Chest pain type (0-3).
- `trestbps`: Resting blood pressure (mm Hg).
- `chol`: Serum cholesterol (mg/dl).
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = True; 0 = False).
- `restecg`: Resting electrocardiographic results (0-2).
- `thalach`: Maximum heart rate achieved.
- `exang`: Exercise-induced angina (1 = Yes; 0 = No).
- `oldpeak`: ST depression induced by exercise relative to rest.
- `slope`: The slope of the peak exercise ST segment (0-2).
- `ca`: Number of major vessels (0-3) colored by fluoroscopy.
- `thal`: Thalassemia (1-3).
- `target`: Diagnosis of heart disease (1 = Disease; 0 = No Disease).
- 
## 🔍 Data Preprocessing
The dataset underwent the following preprocessing steps:

- **Handling Missing Values**: Checked and imputed missing data where necessary.
- **Feature Encoding**: Converted categorical features into numerical format.
- **Feature Scaling**: Normalized continuous variables for better model performance.
- **Train-Test Split**: The dataset was split into **training** and **testing** data.

## 🤖 Model Selection and Training
The following machine learning models were tested:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

## 📌 Key Findings
- `cp` (chest pain type), `thalach` (maximum heart rate), and `oldpeak` (ST depression) are the most influential factors in predicting heart disease.
- Random Forest outperformed other models in terms of accuracy and reliability.
- The dataset contains some class imbalance, which may impact model performance.

## 📜 Conclusion
This project successfully applies machine learning techniques to predict heart disease based on patient data. The insights gained can help healthcare professionals in early diagnosis and prevention strategies.
