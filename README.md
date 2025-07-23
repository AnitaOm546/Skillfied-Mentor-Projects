# 💳 Credit Card Fraud Detection

## 🎯 Objective  
Detect fraudulent credit card transactions using supervised machine learning models.

---

## 📂 Dataset Overview  
The dataset includes anonymized credit card transaction data with the following features:

- **Time**: Seconds elapsed between each transaction and the first transaction  
- **Amount**: Transaction amount  
- **V1 to V28**: Principal components from PCA transformation to protect confidentiality  
- **Class**: Target variable — `1` for fraud, `0` for non-fraud  

The dataset is highly imbalanced, with only a small fraction of transactions labeled as fraudulent.

---

## 🔀 Workflow  

1. **Data Loading & Exploration**  
   - Analyze class distribution and feature statistics  
   - Visualize transaction patterns  

2. **Handling Class Imbalance**  
   - Apply techniques like undersampling, oversampling (SMOTE), or stratified splitting  

3. **Preprocessing & Model Training**  
   - Feature scaling (StandardScaler)  
   - Train models such as Logistic Regression, Random Forest, XGBoost  

4. **Model Evaluation**  
   - Use metrics suitable for imbalanced data:  
     - Precision, Recall, F1-Score  
     - ROC-AUC  
     - Confusion Matrix  

---

## 📊 Tools & Libraries  
- Python, Pandas, NumPy  
- Scikit-learn, XGBoost  
- Matplotlib, Seaborn  

---

## ✅ Outcome  
Achieved improved fraud detection accuracy while minimizing false positives. The project highlights the importance of handling imbalanced data and selecting appropriate evaluation metrics.
