# Health-Fraud-Detection
## 🏥 Healthcare Fraud Detection

Health insurance fraud contributes to significant financial leakage each year. This project develops an **end-to-end machine learning pipeline** to identify high-risk and potentially anomalous healthcare claims for targeted auditing, while balancing predictive performance with model transparency.

The dataset contains historical healthcare claim records enriched with financial and operational indicators, including:

* **Claim Amount**
* **Approved Amount**
* **Unapproved Amount**
* **Cost Per Day**
* **Days Between Service and Claim**
* Other claim, provider, and operational attributes

The project applies machine learning to identify patterns associated with potentially fraudulent claims and uses **explainable AI techniques** to help understand the factors contributing to model predictions.

### 🎯 Project Objectives

* Identify claims with a higher likelihood of fraud
* Develop a robust classification pipeline
* Address class imbalance in healthcare fraud data
* Evaluate predictive performance using multiple metrics
* Identify important features influencing predictions
* Provide interpretable results that can support human auditing and investigation

### 🤖 Machine Learning Approach

The project uses **XGBoost** for fraud classification and **SHAP (SHapley Additive exPlanations)** for model interpretability.

**Modeling pipeline:**

`Data Preparation → Feature Engineering → Class Imbalance Handling → XGBoost → Model Evaluation → SHAP Explainability`

### 🛠️ Technologies

`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `XGBoost` · `SHAP` · `Matplotlib`
