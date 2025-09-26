# Credit EDA Case Study  

This project focuses on performing Exploratory Data Analysis (EDA) on credit-related datasets to identify key factors influencing loan default behavior. The goal is to help financial institutions make informed lending decisions, minimize risk exposure, and improve loan approval strategies.  

## Problem Statement  
The main objective is to detect patterns and variables that affect a client’s likelihood of defaulting on loans. Insights from this study can:  
- Improve loan approval decision-making  
- Reduce risk of issuing loans to high-risk candidates  
- Develop strategies to lower non-performing loans  
- Ensure credit is provided fairly to clients with repayment capability  

## Assumptions  
- Outliers were retained to preserve data integrity  
- Columns with more than 40% missing values were dropped  
- Remaining missing values handled with imputation techniques  
- Special cases like "XNA" and "XAP" were replaced or dropped depending on relevance  

## Approach & Methodology  
1. Business understanding: clarified objectives and domain context  
2. Data loading and exploration of application, previous application, and merged datasets  
3. Data cleaning: removed irrelevant columns, handled missing and special values  
4. Outlier detection and handling: retained due to importance in risk analysis  
5. Imbalance check: measured skew between defaulters (Target=1) and non-defaulters (Target=0)  
6. Exploratory Data Analysis (EDA): performed univariate, segmented univariate, and bivariate analyses  
7. Derived insights and business recommendations  

## Key Insights  
- Middle and low-income groups show higher default rates  
- Strong class imbalance exists between defaulters and non-defaulters  
- Key indicators of risk include: AMT_CREDIT, AMT_INCOME_TOTAL, EXT_SOURCE scores  
- Family status and education influence default probability  
- Consumer loans carry higher default risk than other types  
- Previous application history provides valuable predictive insights  

## Recommendations  
- Build risk models using income-to-credit ratios and external source scores  
- Customize loan policies for specific demographic groups  
- Apply stricter rules for high-risk loan categories  
- Set credit limits to prevent over-leveraging  
- Use sampling/SMOTE techniques to address data imbalance  
- Engineer new features for stronger predictive models  

## Tech Stack  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook for analysis  
- PDF/PPT reports for documentation and presentation  

## Applications  
This project provides a foundation for developing credit risk prediction systems that financial institutions can use to:  
- Enhance approval workflows  
- Reduce default rates  
- Personalize lending policies  
- Strengthen overall risk management  
