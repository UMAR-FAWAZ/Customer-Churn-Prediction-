# Customer-Churn-Prediction-
This is a customer churn prediction analysis

## Business Uderstanding

The objective of this project is to examine and forecast customer attrition within Vodafone, a telecommunications company in Ghana. The main objective is to create a reliable model for predicting churn, identifying customers who are at risk of leaving and comprehending the factors that contribute to churn. The dataset is comprised of three sections: the training dataset, the evaluation dataset, and the test dataset.


## Understanding The Problem

Customer attrition, or churn, is a significant concern for organizations. It represents the percentage of customers who stop using a company's product or service within a specified timeframe. This project aims to assess the likelihood of customer churn, identify key indicators, and propose retention strategies. The objective is to empower the organization to proactively address customer attrition.


## Importance of this project to every Organization

Addressing customer attrition is crucial for the following reasons:
1. **Revenue Protection:** Retaining existing customers is cost-effective, safeguarding established revenue streams.

2. **Customer Lifetime Value (CLV):** Addressing attrition maximizes the long-term value of customers.

3. **Brand Reputation and Loyalty:** Effective attrition management enhances brand reputation and fosters loyalty.

## Data Structure

### I. Data Collection and Analysis

Three datasets are used for this analysis, located in different places:

A. **First Dataset - Customer Churn Data:**
   - Comprises the first 3000 records of customer churn data.
   - Stored in a remote SQL server, accessed using ODBC or SQLAlchemy.
   - Retrieved and converted to a .csv file.

B. **Second Dataset - CSV File with 2000 Records:**
   - A CSV file containing 2000 records.
   - No additional connection is required.

C. **Third Dataset - Test Dataset:**
   - Integral to project evaluation and in CSV format.

The project encompasses a holistic approach, from understanding the business problem to comprehensive data analysis, aiming to provide actionable insights for effective churn management.

| Column           | Description                                           |
|------------------|-------------------------------------------------------|
| Gender           | Whether the customer is a male or a female            |
| SeniorCitizen    | Whether a customer is a senior citizen or not          |
| Partner          | Whether the customer has a partner or not (Yes, No)   |
| Dependents       | Whether the customer has dependents or not (Yes, No)  |
| Tenure           | Number of months the customer has stayed with the company |
| Phone Service    | Whether the customer has a phone service or not (Yes, No) |
| MultipleLines    | Whether the customer has multiple lines or not        |
| InternetService  | Customer's internet service provider (DSL, Fiber Optic, No) |
| OnlineSecurity   | Whether the customer has online security or not (Yes, No, No Internet) |
| OnlineBackup     | Whether the customer has online backup or not (Yes, No, No Internet) |
| DeviceProtection | Whether the customer has device protection or not (Yes, No, No internet service) |
| TechSupport      | Whether the customer has tech support or not (Yes, No, No internet) |
| StreamingTV      | Whether the customer has streaming TV or not (Yes, No, No internet service) |
| StreamingMovies  | Whether the customer has streaming movies or not (Yes, No, No Internet service) |
| Contract         | The contract term of the customer (Month-to-Month, One year, Two years) |
| PaperlessBilling | Whether the customer has paperless billing or not (Yes, No) |
| Payment Method   | The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic)) |
| MonthlyCharges   | The amount charged to the customer monthly            |
| TotalCharges     | The total amount charged to the customer              |
| Churn            | Whether the customer churned or not (Yes or No)       |
