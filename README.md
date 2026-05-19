# procurement-recommendation-score
A supply chain analytics project that builds a structured, data-driven framework for supplier evaluation and selection, drawing inspiration from the US Department of Defense's Supplier Performance Risk System (SPRS). 
Working in a DoD defense contracting environment daily means seeing firsthand how supplier selection decisions can make or break operational continuity. This project takes those real-world principles and adapts them for civilian supply chains by combining supplier performance scoring, product criticality classification, and predictive modelling into a single procurement decision-support framework.
## What this project covers:
Supplier Performance Score (SPS) built from five KPIs — defect rate, compliance, cost efficiency, negligence, and cancellation rate. 
Product Criticality Score (PCS) assigned using Kraljic Matrix principles. 
Procurement Recommendation Score (PRS) derived by combining SPS and PCS for risk-adjusted supplier-product allocation. 
Logistic Regression model to predict order compliance. 
Random Forest Regression model to forecast defect rates at order level. 
Prescriptive buffer stock recommendations based on predicted defect risk.
## Tools used: 
Python, pandas, scikit-learn, matplotlib, seaborn
## Dataset: 
Public procurement KPI dataset via Kaggle

This started as a university assignment. It ended up being something worth building properly.
