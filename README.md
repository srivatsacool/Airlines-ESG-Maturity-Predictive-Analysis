# ✈️ Airlines ESG Maturity Predictive Analysis

<p align="center">
  <img src="assets/hero.png" alt="Airlines ESG Hero Banner" width="100%" />
</p>

## Overview

A comprehensive **data mining project** analyzing ESG (Environmental, Social, Governance) maturity across **127 airline companies** using supervised learning. The project builds predictive models to forecast continuous ESG scores via Linear Regression and classify airlines as ESG Leaders or Laggards via Logistic Regression — achieving **R² = 0.78** and **88% classification accuracy**.

---

## Key Results

| Metric | Value |
|---|---|
| Regression R² | 0.78 (78% variance explained) |
| Classification Accuracy | 88% |
| ROC-AUC | 0.94 (Excellent) |
| Statistical Finding | Large-cap airlines score 12.8 pts higher (p < 0.001) |

---

## Key Features

- **Dual Model Pipeline** — Linear Regression + Logistic Regression
- **Hypothesis Testing** — t-test proving company size affects ESG scores
- **9-Slide Analysis** — Structured presentation-ready output
- **Feature Selection** — VIF-based multicollinearity reduction
- **Comprehensive EDA** — Correlation heatmaps, distributions, box plots

---

## Technology Stack

| Technology | Purpose |
|---|---|
| Python 3 | Core language |
| Scikit-learn | ML models and evaluation |
| Pandas / NumPy | Data manipulation |
| Matplotlib / Seaborn | Data visualization |
| Jupyter Notebook | Interactive analysis |
| StatsModels | Statistical testing |

---

## Methodology

```text
127 Airlines (3 Excel sheets: ENV, Social, Governance)
        ↓
Data Cleaning (IQR outlier removal, median imputation)
        ↓
EDA + Hypothesis Testing (t-test, p < 0.001)
        ↓
Feature Selection (VIF-based)
        ↓
Linear Regression → Continuous ESG Score
Logistic Regression → Leader / Laggard Classification
        ↓
Model Diagnostics (R², RMSE, ROC-AUC, Confusion Matrix)
```

---

## Installation & Setup

```bash
git clone https://github.com/srivatsacool/Airlines-ESG-Maturity-Predictive-Analysis.git
cd Airlines-ESG-Maturity-Predictive-Analysis
pip install -r requirements.txt
jupyter notebook
```

---

## Author

**Srivatsa Gorti**

---
