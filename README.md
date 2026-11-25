# Machine Learning in Finance: Course Exercises & Portfolio

## Repository Overview
This repository contains my weekly coding exercises and data science projects for the **Machine Learning in Finance** course, part of the MPhil in Economics program at the National and Kapodistrian University of Athens (NKUA). 

It serves as a portfolio documenting my progress in applying Python, data analysis techniques, and machine learning algorithms to real-world financial datasets.

## Technologies & Tools
* **Programming Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebooks

## Exercises Directory

Below is the structured list of my weekly projects:

### Week 1: Apple Stock Behavior Analysis
* **File:** [`01_Apple-Stock-Behavior-Python.ipynb`](./01_Apple-Stock-Behavior-Python.ipynb)
* **Data Source:** Financial charting dataset containing Apple stock prices (`AAPL`, 2015–2017).
* **Description:** An exploratory data analysis focusing on Apple's daily lowest price behavior relative to its technical lower Bollinger band. The notebook investigates price movements over time to identify trends, skewness, and volatility clustering during periods of extreme downward pressure.

### Week 2: Demographic Vulnerabilities and Payment Delay Patterns
* **File:** [`02_Demographic_Vulnerabilities_and_Payment_Delay_Patterns.ipynb`](./02_Demographic_Vulnerabilities_and_Payment_Delay_Patterns.ipynb)
* **Data Source:** Anonymized customer dataset containing demographic metrics (e.g., age, income, location) and transaction/billing history.
* **Description:** An exploratory data analysis focusing on identifying core correlations between specific demographic factors and recurring patterns or trends in payment delays.

### Week 3: Credit Risk Analysis and Pipeline Engineering
* **File:** [`03_Credit_Risk_Analysis_and_Pipeline_Engineering.ipynb`](./03_Credit_Risk_Analysis_and_Pipeline_Engineering.ipynb)
* **Data Source:** UCI Credit Card Default Dataset.
* **Description:** An advanced data engineering and analysis project focused on building structured preprocessing pipelines (`ColumnTransformer`, `Pipeline`, `StandardScaler`, `OneHotEncoder`) to prevent data leakage. Additionally, it investigates default behavior in high credit limit outliers, evaluating whether their risk stems from excessive borrowing or liquidity management constraints.

### Week 4: Evaluating Consumer Credit Risk
* **File:** [`04_Evaluating_Consumer_Credit_Risk.ipynb`](./04_Evaluating_Consumer_Credit_Risk.ipynb)
* **Data Source:** Consumer credit risk dataset (50k loan records).
* **Description:** A machine learning and risk modeling project focused on evaluating consumer creditworthiness, feature importance, and predictive classification metrics for loan default risk.

### Week 5: Early Credit Card Default Prediction — Transparent Logistic Baseline
* **File:** [`05_Early_Default_Warning.ipynb`](./05_Early_Default_Warning.ipynb)
* **Data Source:** Credit Card Cardholder Snapshot Dataset ($N = 1,000$ accounts, $20$ engineered features).
* **Description:** An end-to-end, leakage-free credit risk modelling pipeline built to flag active credit cardholders at risk of next-month default for early preventive intervention. The notebook compares Ridge ($L_2$), LASSO ($L_1$), and Elastic Net regularised logistic regressions via 5-fold cross-validation (`Test ROC-AUC = 0.7845`, `Test Log-Loss = 0.4385`), translates coefficients into odds multipliers ($\exp(\beta_j)$), and evaluates cost-sensitive decision thresholds ($c = 0.20$ vs. $c = 0.50$) to balance false alarms against unflagged credit losses.

