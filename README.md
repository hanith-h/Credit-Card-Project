# 💳 CREDIT CARD PROJECT – PHASE 1  

---

## 📖 OVERVIEW  
This project focuses on **CREDIT CARD FRAUD DETECTION** using **MACHINE LEARNING** techniques. The dataset contains anonymized credit card transaction data, where the task is to identify fraudulent transactions.  

The project addresses the challenge of **IMBALANCED DATA**, since fraudulent cases are significantly fewer compared to non-fraudulent ones.  

---

## 📂 REPOSITORY STRUCTURE  
```
CREDIT-CARD-PROJECT/
│── Credit Card Project-Phase1.ipynb   # MAIN NOTEBOOK
│── README.md                          # PROJECT DOCUMENTATION
│── data/                              # DATASET FILES (NOT INCLUDED IN REPO)
```

---

## 📊 DATASET INFORMATION  
- **DESCRIPTION**: Transactions made by European cardholders in September 2013.  
- **SIZE**: 284,807 transactions  
- **CLASSES**:  
  - `0` → LEGITIMATE TRANSACTION  
  - `1` → FRAUDULENT TRANSACTION  
- **FEATURES**:  
  - Most features are anonymized (`V1`, `V2`, …, `V28`).  
  - `Time` and `Amount` are original features.  
  - `Class` is the target label.  

---

## ⚙️ PROJECT WORKFLOW  
1. **IMPORT LIBRARIES** – PANDAS, NUMPY, MATPLOTLIB, SEABORN, SCIPY, SCIKIT-LEARN, IMBLEARN  
2. **DATA LOADING** – LOAD CREDIT CARD DATASET  
3. **DATA PREPROCESSING** –  
   - HANDLING MISSING VALUES  
   - FEATURE SCALING  
   - TRAIN-TEST SPLIT  
4. **EDA (EXPLORATORY DATA ANALYSIS)** –  
   - DATA DISTRIBUTION  
   - CLASS BALANCE CHECK  
   - FEATURE CORRELATIONS  
5. **IMBALANCE HANDLING** – APPLY **SMOTE / RESAMPLING** USING **IMBLEARN**  
6. **MODEL TRAINING** – IMPLEMENT MACHINE LEARNING MODELS:  
   - LOGISTIC REGRESSION  
   - DECISION TREE CLASSIFIER  
   - RANDOM FOREST CLASSIFIER  
   - GRADIENT BOOSTING / XGBOOST (IF USED)  
7. **MODEL EVALUATION** –  
   - CONFUSION MATRIX  
   - PRECISION, RECALL, F1-SCORE  
   - ROC-AUC  

---

## 🚀 HOW TO RUN LOCALLY  
1. **CLONE THE REPOSITORY**  
   ```bash
   git clone https://github.com/your-username/CREDIT-CARD-PROJECT.git
   cd CREDIT-CARD-PROJECT
   ```  

2. **INSTALL DEPENDENCIES**  
   ```bash
   pip install -r requirements.txt
   ```  

3. **RUN NOTEBOOK**  
   ```bash
   jupyter notebook "Credit Card Project-Phase1.ipynb"
   ```  

---

## 📈 RESULTS SUMMARY  
- **IMBALANCED DATA** was successfully handled using **SMOTE / RESAMPLING TECHNIQUES**.  
- MACHINE LEARNING MODELS were trained and evaluated, with **ENSEMBLE METHODS** (Random Forest / Gradient Boosting) performing better than simple Logistic Regression.  
- **ROC-AUC SCORES** and **RECALL** were prioritized, since identifying fraud correctly is more critical than minimizing false positives.  

---

## 📚 REFERENCES  
- KAGGLE – https://www.kaggle.com/mlg-ulb/creditcardfraud  
- IMBALANCED-LEARN DOCUMENTATION – https://imbalanced-learn.org  
- SCIKIT-LEARN DOCUMENTATION – https://scikit-learn.org  
