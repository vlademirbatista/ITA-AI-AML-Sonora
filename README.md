# Sonora – An Autonomous Analyst for AML

This repository contains the reproducible codebase for **Sonora**, an autonomous analyst based on **Explainable Artificial Intelligence (XAI)**, designed to support **Anti-Money Laundering (AML)** activities in financial institutions.  

Sonora was developed as part of a Master’s dissertation at the Instituto Tecnológico de Aeronáutica (ITA), Brazil, focusing on combining **high recall performance** with **interpretability** to meet the regulatory and operational demands of AML monitoring.  

---

## 🔍 Overview

AML monitoring is a critical function for financial institutions but faces two main challenges:
- **Data imbalance**: suspicious transactions are rare compared to legitimate ones.  
- **Complexity of illicit strategies**: criminal actors constantly adapt to conceal the origin of resources.  

Sonora addresses these issues by combining:
- Gradient Boosting–based predictive modeling (with hyperparameter optimization).  
- Threshold-oriented evaluation, prioritizing **recall** over accuracy to reduce regulatory risks.  
- SHAP-based explanations to enhance transparency and support human analysts.  

---

## 📂 What’s Inside

- `ITA_AI_AML_SONORA_20251004.ipynb`: main notebook with the full pipeline.  
- Data preparation and cleaning routines.  
- Model training and evaluation (Gradient Boosting, XGBoost as baseline).  
- Threshold analysis and performance metrics (recall, precision, F1, ROC, PR curves).  
- SHAP-based global and local explanations for interpretability.  

---

## ⚙️ Requirements

- Python 3.10+  
- Main libraries:
  - `pandas`, `numpy`, `scikit-learn`  
  - `xgboost`  
  - `shap`  
  - `matplotlib`, `seaborn`  

Install all dependencies with:  

```bash
pip install -r requirements.txt
