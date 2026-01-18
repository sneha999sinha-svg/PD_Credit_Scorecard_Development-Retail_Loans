# PD & Credit Scorecard Development – Retail Loans

## Project Overview

This project demonstrates the end-to-end development of a **Probability of Default (PD) scorecard** for retail loan portfolios using **logistic regression** and **Weight of Evidence (WoE)**.
The objective is to build an **interpretable, governance-friendly credit risk model** aligned with industry-standard risk practices.

---

## Key Objectives

* Estimate **Probability of Default (PD)** for retail borrowers
* Create an **interpretable scorecard** suitable for risk decisioning
* Evaluate model performance and **monitor stability over time**
* Document assumptions and limitations to support **risk governance**

---

## Methodology

1. **Data Preparation**

   * Data cleaning, missing value treatment, and outlier handling
   * Feature selection based on business intuition and statistical relevance

2. **Binning & Transformation**

   * Optimal binning of variables
   * Weight of Evidence (WoE) transformation
   * Information Value (IV)–based variable assessment

3. **Model Development**

   * Logistic regression–based PD model
   * Scorecard scaling and point allocation

4. **Model Evaluation**

   * AUC: 0.82
   * Gini: 64%
   * KS: 38%

5. **Stability & Monitoring**

   * Population Stability Index (PSI) to assess model robustness

---

## Risk & Controls Relevance

This project emphasizes **model interpretability, documentation, and monitoring**, which are critical from a **risk and controls perspective**:

* Transparent variable selection and rationale
* Clearly stated assumptions and limitations
* Performance and stability monitoring to support ongoing risk oversight

---

## Tools & Technologies

* Python (Pandas, NumPy, Scikit-learn)
* Logistic Regression
* WoE / IV
* Matplotlib / Seaborn

---

## Disclaimer

This project is for **educational and demonstration purposes only**.
It does not represent a production model or real lending decisions.

---
