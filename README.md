# 🛡️ Credit Card Fraud Detection

This project applies **machine learning** techniques to detect fraudulent credit card transactions.  
The dataset is highly **imbalanced**, with fraud cases making up only about **0.17%** of all transactions.

---

## 📊 Dataset
- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
 
- Features: anonymized PCA components (`V1`...`V28`), `Amount`, and `Time`.

---

## 🚀 Project Workflow
1. **Exploratory Data Analysis (EDA)**  
   - Transaction amount distribution (Fraud vs Normal).  
   - Class imbalance visualization.  

2. **Preprocessing**  
   - Train/test split with stratification (preserve fraud ratio).  
   - Feature scaling using `StandardScaler`.  

3. **Models Used**  
   - **Logistic Regression** (baseline).  
   - **Random Forest** (supervised, feature importance).  
   - **Isolation Forest** (unsupervised anomaly detection).  

4. **Evaluation Metrics**  
   - Confusion Matrix  
   - Classification Report (Precision, Recall, F1-score)  
   - **ROC Curve**  
   - **Precision-Recall Curve**  

---

## 📈 Results & Visuals
- Fraud transactions are generally lower in amount than normal ones.  
- **Random Forest** performs best among supervised models.  
- **Isolation Forest** detects anomalies without labels but less accurate.  

Example Graphs:
- Transaction Amount Distribution  
- Feature Importances (Random Forest)  
- ROC & Precision-Recall Curves  

---

