# Loan-Risk-Predictor
A loan is a financial agreement in which a bank or financial institution provides a borrower with a specific amount of money, which must be repaid over time with interest.The Loan Risk Prediction System is a machine learning-based model designed to assess the risk associated with loan applications. The system evaluates various financial and other parameters to classify loan applications into risk categories (Low, Medium, High). This helps banks and financial institutions in making effecient lending decisions, and setting appropriate interest rates.
## Risk deciding 
Since the original dataset does not contain risk column so it has to be added, risk is classified in three categories (High,Medium,Low) based on several industry standard factors,using percentile function to get the best threshold values for this particular dataset and critical thinking.
## Features
- Automated Risk Assessment: Predicts the risk level of loan applicants.
- Data-Driven Decision Making: Uses historical data to train predictive model
- Scalability: Can be extended to support different risk evaluation metrics.
- Explainability: Feature importance analysis to understand risk factors.
## Risk Classification Criteria
Risk levels are assigned based on a weighted scoring system using these parameters:
- Loan-to-Value Ratio (LTV)
- Loan Amount
- Interest Rate
- Debt-to-Income Ratio (DTI)
- Property Value
- Credit Type & Co-applicant Credit Type
- Credit Worthiness
- Loan Status
- Occupancy Type
## Machine Learning Models Used
- Decision Tree Classifier
- Random Forest Classifier
- LightGBM
- Logistic Regression
- XGB
