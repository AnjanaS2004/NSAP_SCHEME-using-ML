# Predicting NSAP Scheme Eligibility Using Machine Learning

A capstone project aimed at automating and enhancing the efficiency of beneficiary classification under the National Social Assistance Program (NSAP) using Machine Learning.

## 🚀 Project Overview

Manually processing applications for NSAP welfare schemes (for the elderly, widows, and persons with disabilities) is often slow and error-prone. This project builds a predictive model using demographic and socio-economic data to automatically classify applicants into appropriate schemes.

---

## 🎯 Problem Statement

The manual approach to verifying and assigning NSAP schemes can:
- Delay assistance to deserving individuals.
- Introduce human errors.
- Overburden administrative staff.

## ⚙️ System Workflow

1. **Input Features**: Age, gender, income, marital status, disability status, household type, etc.
2. **Preprocessing**:
   - Null value handling
   - Categorical encoding
   - Normalization
3. **Training**:
   - Labeled demographic data
   - Model tuned for multi-class classification
4. **Evaluation**:
   - Accuracy (~99%)
   - Precision, Recall, F1-Score
   - Confusion Matrix
5. **Deployment**:
   - Exported with `joblib`
   - Hosted using Flask or Streamlit
   - Role-based access and privacy protocols ensured

---

## 🛠️ Tech Stack

| Component       | Technology            |
|----------------|------------------------|
| Programming     | Python                 |
| Data Handling   | Pandas, NumPy          |
| ML Algorithms   | Scikit-learn           |
| Visualization   | Matplotlib, Seaborn    |
| Deployment      | Flask / Streamlit, IBM Cloud or AWS |
| Data Source     | Simulated / anonymized demographic dataset |

---

## 📈 Results

- Achieved **~99% accuracy**
- Model effectively distinguishes between:
  - IGNOAPS (Old Age)
  - IGNWPS (Widow)
  - IGNDPS (Disabled)
- Confusion matrix shows excellent class separation

---

## 🔭 Future Scope

- Real-time integration with government databases
- Expansion to include state-level schemes
- Incorporate Explainable AI (XAI) for policy transparency
- Implement continuous learning via user feedback
