# DS-2010-Project-Mental-Health-In-Tech
Machine learning project predicting mental health treatment in tech employees
# Mental Health in Tech - Machine Learning Project

## 📌 Overview
This project analyzes whether workplace conditions can predict if a tech employee will seek mental health treatment.

The goal is to combine statistical analysis and machine learning to identify key factors influencing mental health decisions.

---

## 🎯 Objective
To predict whether an individual seeks mental health treatment based on:
- Workplace environment
- Personal background
- Company-related factors

---

## 📊 Dataset
- Source: OSMI Mental Health in Tech Survey (Kaggle)
- Total responses: 1,259
- Features: 27 (demographic + workplace-related)

---

## 🧹 Data Preprocessing
- Removed missing values
- Cleaned inconsistent entries (e.g., gender formatting)
- Selected important features:
  - Age
  - Company size
  - Family history
  - Workplace support
- Handled inconsistencies and ensured data quality

---

## 📈 Exploratory Data Analysis
Key insights:
- Treatment distribution is relatively balanced
- Most respondents are aged 25–35
- Strong relationships observed between:
  - Family history and treatment
  - Work interference and treatment
  - Company size and treatment

---

## 📊 Statistical Analysis
- Chi-square test showed a significant relationship between workplace factors and treatment
- Cramér’s V indicated moderate association strength
- Confirms that key variables influence treatment decisions

---

## 🤖 Machine Learning Models
Two models were used:

### 1. Logistic Regression
- Accuracy: ~81%

### 2. Random Forest
- Accuracy: ~80%

### Data Split
- 80% Training
- 20% Testing

---

## 🔍 Feature Importance
Top predictors:
- Family history (strongest predictor)
- Work interference
- Workplace benefits

---

## 📌 Key Findings
- Family history is the most important factor
- Workplace conditions significantly impact mental health decisions
- Machine learning models confirm patterns found in statistical analysis
- Simple models perform effectively, indicating clear relationships in data

---

## ⚠️ Limitations
- Data is self-reported (possible bias)
- Dataset mainly represents tech workers
- Results may not generalize to other industries
- Correlation does not imply causation

---

## 💡 Conclusion
Both statistical analysis and machine learning show that workplace conditions and personal background strongly influence mental health treatment behavior.

---

## 🚀 Future Improvements
- Use more diverse datasets
- Apply advanced models (e.g., XGBoost, Neural Networks)
- Include real-time or longitudinal data

---

## 🔗 Project Links

### 📓 Colab Notebook
https://colab.research.google.com/drive/1BoBpiduhuc3U4U_LzN2RDk-oPANnB99Q?usp=sharing

### 📊 Presentation Slides
https://canva.link/5ue8gdtobrplndv

### 🎥 Presentation Video
(Paste your video link here after uploading)

---

## 👤 Author
Prakash Nihal
