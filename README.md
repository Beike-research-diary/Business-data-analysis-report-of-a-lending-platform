# Business-data-analysis-report-of-a-lending-platform
This is a self-directed learning project that outputs a Python based report containing data cleansing, business analysis and optimization recommendations.
## Partial Overview
### User profile analysis
![image](https://github.com/user-attachments/assets/999c7cb8-b4be-4b7a-b52e-8f63792a82b2)
### User repayment analysis
![image](https://github.com/user-attachments/assets/52d4f8c1-fe0d-4876-bef4-e53341a85461)
### RFM model customers layering
![image](https://github.com/user-attachments/assets/9c1c8de2-6850-4b4a-be0e-57eae3030f4e)
## What I learned from this project
Processed 3.2M+ repayment records with Pandas: Cleaned datetime formats, converted categorical authentication fields to booleans, and merged multi-table datasets.  
Conducted EDA using Seaborn/Matplotlib: Analyzed loan type distributions, age segmentation, and gender-based repayment patterns through bar charts and pie plots.   
Built RFM model with dynamic binning: Handled skewed frequency data (all users had only 1 loan) by focusing on Recency and Monetary dimensions for value stratification.  
Automated data validation: Checked duplicates via ListingId uniqueness and age range consistency (17-56 years).  
Applied survival analysis (Kaplan-Meier) to reveal 0% repeat-borrow rate, prompting product redesign discussions.  
