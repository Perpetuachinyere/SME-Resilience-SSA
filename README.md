
# SME Resilience in Sub-Saharan Africa: A Hybrid OLS-ML Analysis

This repository contains the Python implementation and analytical code for the study: 
**"Sustainable Venture Capital, Entrepreneurial Resilience, and ESG Integration Among SMEs in Sub-Saharan Africa: A Multi-Country Study."**

## Overview
The project utilizes a Two-Stage Hybrid Analytical Engine to investigate SME resilience:
- **Stage I:** Statistical Inference using OLS Structural Path Analysis.
- **Stage II:** Predictive Stress-Testing using XGBoost and Random Forest.
- **Explainability:** SHAP (SHapley Additive exPlanations) for model transparency.

   ## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook
2. Install required libraries
3. Run all cells sequentially

## Outputs
- Feature importance rankings (RF, XGB)
- SHAP value analysis
- Model performance metrics

## Contents
- `SME_Resilience_Analysis.ipynb`: The primary Google Colab/Jupyter notebook containing the full pipeline.
- `requirements.txt`: List of necessary Python libraries (XGBoost, SHAP, Scikit-learn, etc.).

## Data Source
Analysis is based on the **2023 World Bank Enterprise Survey (WBES)** microdata for Nigeria, Ghana, Kenya, and South Africa.
