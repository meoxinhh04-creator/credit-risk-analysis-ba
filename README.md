## Credit Risk Analysis – Business Analyst Perspective

### Business Objective
Analyze customer credit risk to support loan approval decisions and reduce default risk in the finance and banking domain.

### Business Context
The project focuses on evaluating customer creditworthiness using historical lending data, supporting business stakeholders in making data-driven credit decisions.

### Dataset
Lending Club dataset with over 1.3 million loan records, including customer information, loan characteristics, and repayment status.

### Business Analysis & Data Preparation
- Analyzed the business problem of credit risk assessment and default prediction.
- Performed data cleaning, missing value handling, feature encoding, and data leakage detection.
- Conducted exploratory data analysis (EDA) to identify key factors affecting default risk such as interest rate, FICO score, income, and debt-to-income ratio (DTI).

### Decision Support & Modeling
- Built and compared predictive models to support credit risk evaluation.
- Evaluated model performance to identify the most suitable approach for practical use.
- Translated analytical results into insights to support business decision-making.

### Key Insights
- Credit risk is strongly influenced by interest rate, credit score, income, and DTI.
- Data-driven analysis helps improve loan approval accuracy and reduce potential default losses.

### Tools & Technologies
Python, Pandas, NumPy, Scikit-learn, SQL (basic), HTML (basic), Data Visualization

### Project Documentation
Full project report (PDF): https://drive.google.com/file/d/175fJiJsHYSm1At2kElApw-tQOxKlZFaA/view?usp=sharing

## Exploratory Data Analysis (EDA)

This section presents key exploratory analyses on important numerical variables to understand customer characteristics and credit risk patterns.

### Loan Amount Distribution
![Loan Amount Distribution](diagrams/loan_amnt_imp_histogram.png.png)

> The histogram shows the distribution of loan amounts, indicating that most customers borrow relatively small to medium loan values, which is important for assessing exposure and risk concentration.

---

### Interest Rate Distribution
![Interest Rate Distribution](diagrams/int_rate_imp.png)

> Higher interest rates are more frequently associated with riskier customer segments, reflecting risk-based pricing strategies in lending decisions.

---

### Debt-to-Income (DTI) Distribution
![DTI Distribution](diagrams/dti_imp_1.png)
![DTI Distribution](diagrams/dti_imp_2.png)


> Customers with higher DTI ratios tend to exhibit higher financial pressure, which can increase the likelihood of loan default.

---

### FICO Score (Low Range) Distribution
![FICO Low Range Distribution](diagrams/fico_range_low_imp_1.png)

> Lower FICO score ranges show higher risk concentration, confirming credit score as a critical factor in credit risk evaluation.

---

### FICO Score (High Range) Distribution
![FICO High Range Distribution](diagrams/fico_range_high_imp_2.png)

> Customers with higher FICO scores are more concentrated in lower-risk segments, supporting their use in credit approval and risk segmentation.
### FICO Score – Credit Risk Assessment Insight
![FICO Credit Risk Insight](diagrams/fico_nhan_xet.png)

> This visualization highlights the relationship between FICO score ranges and default risk. Customers with lower FICO scores show significantly higher default rates, reinforcing the importance of credit scoring in loan approval, risk segmentation, and pricing decisions.

### Interest Rate Distribution – Boxplot
![Interest Rate Boxplot](diagrams/boxplot_int_rate_imp.png)

> The boxplot highlights the distribution and outliers of interest rates. Loans with extremely high interest rates are potential high-risk cases, reflecting borrowers with weaker credit profiles and higher default probability.

---

### Debt-to-Income (DTI) Distribution – Boxplot
![DTI Boxplot](diagrams/boxplot_dti.png)

> This boxplot shows the spread and outliers of customers' debt-to-income ratios. High DTI outliers indicate customers under significant financial stress, which is a key risk indicator in credit approval and risk management decisions.

### Default Distribution – Count Bar Chart
![Default Count Bar Chart](diagrams/Count Bar Chart.png)

> This chart compares the number of default and non-default loans, providing an overall view of class distribution. Understanding this imbalance is essential for risk assessment and model evaluation.

---

### Default Rate Comparison – Mean Bar Chart
![Default Mean Bar Chart](diagrams/Mean Bar Chart.png)

> The mean bar chart highlights the average default rate across customer segments, helping identify high-risk groups and supporting data-driven credit approval and risk segmentation strategies.

---

### FICO Score Comparison Across Risk Groups
![FICO Comparison Bar Chart](so sanh fico.png)

> This comparison shows significant differences in FICO scores between default and non-default customers, confirming FICO score as one of the most influential factors in credit risk decision-making.


