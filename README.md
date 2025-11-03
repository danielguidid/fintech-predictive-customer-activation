# fintech-predictive-customer-activation
End-to-end analytics project combining predictive modeling, segmentation, and business strategy o identify high-value customers and design ROI-based growth campaigns for a FinTech company.

# 🏦📱 Fintech Customer Monetization Strategy (easyMoney Case)

**Data Science & Business Strategy Capstone Project – Nuclio Digital School**

This repository contains the capstone project developed for the *Master in Data Science & AI*, focused on designing a **customer reactivation and monetization strategy for a FinTech company easyMoney** using advanced analytics and predictive modeling.

The project combines data engineering, machine learning, customer segmentation, and business strategy to identify high-potential customer groups and design ROI-based marketing campaigns.

---

## 💼 Business Summary

The case study simulates a FinTech named **easyMoney**, which offers multiple financial products such as debit cards, savings accounts, crypto accounts, long-term deposits, and pension plans.

The objective was to:
- Reactivate inactive customers and increase product penetration.
- Build predictive models to estimate **purchase propensity** per product.
- Segment customers into actionable clusters for **targeted marketing campaigns**.
- Design a business proposal estimating **costs, expected ROI, and conversion tiers** per channel.

---

## 🛠 Tech Stack

**Languages:** Python, DAX, Power BI  
**Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost 
**Techniques:** EDA, Feature Engineering, Propensity Modeling, Hyperparameter Tuning, Clustering (K-Means), Campaign Simulation, ROI Estimation  
**Visualization:** Power BI Dashboard

---

## 📂 Repository Structure

### 1. Data Preparation & Feature Engineering
`Limpieza_BD_y_Feature_Engineering.ipynb`  
- Integrates and cleans five datasets.  
- Performs rapid EDA, null imputation, and product-level profitability analysis.  
- Generates engineered features used in predictive models.

### 2. Propensity Models (M1–M5)
- `M1_em_account_Propensión_Compra.ipynb` → EasyMoney Account  
- `M2_emc_account_Propensión_Compra.ipynb` → Crypto Account  
- `M3_pension_plan_Propensión_Compra.ipynb` → Pension Plan  
- `M4_long_term_deposit_Propensión_Compra.ipynb` → Long-Term Deposit  
- `M5_debit_card_Propensión_Compra.ipynb` → Debit Card  

Each notebook includes preprocessing, model training, resampling, hyperparameter tuning, and final predictions.

### 3. Customer Segmentation
`Clustering_Model.ipynb`  
- Performs customer segmentation using **K-Means (k=5)**.  
- Selects key behavioral and financial features to define actionable clusters.

### 4. Business Strategy & Campaign Simulation
`Business_Proposal.ipynb`  
- Builds a business plan with product–segment matching.  
- Simulates **campaign costs, revenues, and ROI** across realistic scenarios.  
- Defines conversion tiers by predicted probability and channel type (email, telesales).

---

## 📂 Additional Files

- `requirements.txt` → Python libraries needed to reproduce results.  
- `Dashboard easyMoney.pdf` → Power BI dashboard summarizing business performance (data version omitted for GitHub size limits).  
- `Memoria TFM.pdf` → Academic report with full methodology and results.  
- `Presentación.pdf` → Executive presentation for stakeholders.  

---

## ⚙️ How to Run

1. Create and activate a virtual environment.  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

---

## 👥 Collaborators

Daniel Guidi

Juan Manuel Guatta

Miguel Ángel García

Raphael Cheves

Master in Data Science & AI – Nuclio Digital School (Barcelona, 2025)

---

## ⚠️ Disclaimer

All notebooks and documentation are written in Spanish, as this project was developed collaboratively within an academic environment.
This README provides an English business and technical overview for recruiters, hiring managers, and collaborators.
