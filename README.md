# Credit-Risk-Fraud-Analytics-Dashboard  
End-to-end credit portfolio risk analysis framework combining predictive modeling, fraud detection, statistical testing, and business-driven risk segmentation.

# Project Overview
This project builds a credit risk and fraud analytics pipeline to evaluate borrower default probability, detect anomalous behavior, and segment portfolio risk for decision-making.

# Key Contributions
-Built a credit default prediction model using Random Forest (ROC–AUC ≈ 0.90), incorporating stratified train–test split and class imbalance handling via weighted learning.

-Performed probability threshold optimization to balance precision–recall trade-offs, improving identification of high-risk borrowers beyond the default 0.5 cutoff.

-Developed an Isolation Forest–based anomaly detection layer to flag suspicious borrower patterns and quantify fraud risk.

-Engineered risk segmentation frameworks, including - DTI-based risk tiers , Income segmentation bands ,Loan-purpose risk analysis using SQL (DuckDB) for  analytical slicing.

-Conducted A/B hypothesis testing (proportion z-test) to compare default rates across 36-month vs 60-month loan terms (no statistically significant difference observed at α = 0.05).

-Created a composite risk index combining fraud and default signals to support portfolio-level prioritization.

-Visualized XGBoost feature importance, identifying key drivers such as income verification status, interest rate, delinquency history, and annual income.

# Tech Stack
Python
Pandas, NumPy
Scikit-learn
XGBoost
Matplotlib / Seaborn
DuckDB (SQL)
Power BI
