# Fraudulent_Claim_Detection
Global Insure wants to build a model to classify insurance claims as either fraudulent or legitimate based on historical claim details and customer profiles.

### Problem Statement

Global Insure, a leading insurance company, processes thousands of claims annually. However, a significant percentage of these claims turn out to be fraudulent, resulting in considerable financial losses. The company’s current process for identifying fraudulent claims involves manual inspections, which is time-consuming and inefficient. Fraudulent claims are often detected too late in the process, after the company has already paid out significant amounts. Global Insure wants to improve its fraud detection process using data-driven insights to classify claims as fraudulent or legitimate early in the approval process. This would minimise financial losses and optimise the overall claims handling process.

### Business Objective
Global Insure wants to build a model to classify insurance claims as either fraudulent or legitimate based on historical claim details and customer profiles. By using features like claim amounts, customer profiles and claim types, the company aims to predict which claims are likely to be fraudulent before they are approved.

### Tasks

- Data Preparation and Understanding
- Data Cleaning
- Train Validation Split 70-30
- EDA on Training Data
- EDA on Validation Data (optional)
- Feature Engineering
- Model Building
- Predicting and Model Evaluation

### Findings

- Claims marked as "**Minor Damage**" are **strongly associated** with fraud. Possibly used to understate damage deliberately. Claims with
minor damage should be flagged for additional verification, as these are more likely to be fraudulent.
- **Higher claim amounts** are **positively associated with fraud** — fraudsters may exaggerate losses. Claims with higher claim amount
should be flagged for additional verification, as these are more likely to be fraudulent.
- People who listed "**chess**" as a hobby had a **higher likelihood** of fraud and should be flagged for additional verification, as these are
more likely to be fraudulent.
- **Higher premiums** may be **correlated with fraud**, possibly because fraudsters target high-value policies. Claims with higher premium
amount should be flagged for additional verification, as these are more likely to be fraudulent.
- "**Total Loss**" incidents are also **strongly linked to fraud** — possibly due to large payouts. Claims with higher total loss amount should
be flagged for additional verification, as these are more likely to be fraudulent. 

### Technologies
- **Python** (Pandas, Numpy, Matplotlib, Seaborn, statsmodels.api, SKLearn)
- Data cleaning & Analysis
- EDA on Training and Validation data
- Logistic Regression and Random Forest

### Author
 > Tejashri Pilla
> 
 > Samrat Chakraborty
