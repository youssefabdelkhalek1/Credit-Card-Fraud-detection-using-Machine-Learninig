# 🤖 Machine Learning Pipeline - credit card fraud detection Project

This project aims to detect fraudulent credit card transactions using a complete machine learning pipeline — from data cleaning and feature engineering to model training, evaluation, and deployment using Streamlit.

##  Problem Statement
Finex, a financial services company, is suffering from major financial losses due to credit card fraud. The goal is to build a system that detects fraudulent transactions in real-time and minimizes financial loss.


## 📁 Project Structure

```
├── milestone_1.ipynb    # Data Collection, ,cleaning and Exploration
├── milestone2.ipynb     # Feature engineering and selection
├── milestone_3.ipynb    # Model selection and evaluation
├── gui.py               # Model deployment using streamlit
```

---

## 🧩 Milestone 1: Data Preprocessing & Exploration

- **Overview**:
  - Data Collection: Use the Credit Card Fraud Detection dataset from Kaggle. Ensure the dataset contains transaction features and  fraud labels. Data set: 
  - Data Preprocessing: Handle missing values (if any) and outliers.
  - Data Exploration (EDA): Understand the structure of the dataset. Analyze class imbalance (percentage of fraud vs. non-fraud transactions). Visualize feature distributions,Explored data through (matplotlib, seaborn). 
  - Conducted advanced statistical analysis.
  - Deliverables: EDA Report: Summary of dataset characteristics, key patterns, and challenges. Preprocessed Dataset: A cleaned and balanced dataset ready for next step.

- **Key Tasks**:
  - Null value handling (though dataset had none).
  - Duplicates removal.
  - Exploratory Data Analysis (EDA):
  - Visualized distributions and patterns using matplotlib and seaborn.
  - Analyzed class imbalance.
  - Detected and retained meaningful outliers.
  - Conducted statistical analysis for pattern discovery.

---

## 🏗️ Milestone 2: Feature Engineering & Selection

- **Overview**:
  - creating new Feature :
  - cust_age, cust_age_groups
  - time_bins, trans_hour
  - fraud_ratio_in_city
  - amount_to_avg_ratio
  - distance_from_merchant
  - Encoded categorical variables (Label Encoding), scaling, and transformation.
  - Performed Feature Selection using:
  - Correlation Matrix
  - Fisher Score
  - Random Forest Feature Importance
  - Removed features with high leakage or redundancy.


- **Key Tasks**:
  - Label encoding .
  - Label Encoding for categorical features (e.g., Gender, Job, Merchant Category).
  - Scaling numerical features using StandardScaler.
  - Feature selection using correlation matrix, Fisher Score, and Random Forest importance.
  - Dropped features with high leakage or redundancy.

---

## 📊 Milestone 3:Model Development Process

- **Overview**:
  - Compared model performances: Algorithms tested: Logistic Regression, Random Forest, XGBoost, LightGBM, Decision Tree
  - Class Imbalance Handling: Explanation of the significant imbalance (191:1 ratio) and why class weights were chosen over resampling techniques
  - Chose the best-performing model based on metrics.
  - Hyperparameter Tuning: The RandomizedSearchCV process that optimized for recall and found the ideal model configuration.
  - Feature Importance
  - Final Model Performance: Detailed metrics including the strong recall scores (97.04% training, 94.89% testing)

---

## 📊 Milestone 4:Deployment and Business Impact

- **Overview**:
  - Deployment Implementation: How the model was serialized and prepared for production use
  - Dashboard Creation: The Streamlit dashboard for monitoring fraudulent and non-fraudulent transactions
  - Financial Impact Analysis: Comprehensive breakdown of costs and benefits
  - Business Value: Impressive 95.4% cost savings ($203,574.96 monthly) achieved through model deployment
  - Performance Trade-offs: Clear explanation of the recall-precision balance and why it aligns with business needs
  - Future Considerations: Suggestions for ongoing model refinement and monitoring

---

## 🛠️ Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas / NumPy
- Scikit-learn
- Seaborn / Matplotlib
- XGBoost / LightGBM (if used)
---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/youssefabdelkhalek1/Credit-Card-Fraud-detection-using-Machine-Learninig.git
   cd Credit-Card-Fraud-detection-using-Machine-Learninig
   ```

3. Run the notebooks using Jupyter:
   ```bash
   jupyter notebook
   ```

---

## 👨‍💻 Author

Made with ❤️ by **[Youssef Mohamed Abdelkhalek]**

Feel free to fork, star, or contribute!