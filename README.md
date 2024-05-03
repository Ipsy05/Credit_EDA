# Loan Default Prediction Case Study 
## Based on Upgrad Credit EDA Assignment

## Business Objectives

This case study aims to identify patterns indicating if a client may have difficulty paying their installments. These patterns can be used to make informed decisions such as denying the loan, adjusting the loan amount, or offering loans at higher interest rates. By identifying such applicants through Exploratory Data Analysis (EDA), the goal is to ensure that clients capable of repaying the loan are not rejected. Additionally, the company seeks to understand the driving factors behind loan default to improve its portfolio and risk assessment strategies.

## Data Understanding

The dataset consists of three files:

1. **'application_data.csv'**: Contains client information at the time of loan application, including indicators of payment difficulties.
2. **'previous_application.csv'**: Provides information about the client's previous loan applications, including their approval status.
3. **'columns_description.csv'**: A data dictionary describing the variables used in the datasets.

## Insights from EDA

- **Data Cleaning**: Initial analysis revealed the need for data processing and cleaning due to missing and unnecessary columns.
- **Missing Values**: Identified columns with missing values and dropped unnecessary columns with high percentages of missing data.
- **Imputation**: Imputed missing values for specific columns such as 'OCCUPATION_TYPE' and 'NAME_TYPE_SUITE'.
- **Outlier Handling**: Capped outliers in columns like 'AMT_CREDIT' and 'AMT_ANNUITY' to mitigate their impact on analysis.
- **Correlation Analysis**: Explored correlations between variables to identify parameters strongly correlated with loan default.
- **Loan Trends**: Found that loans for repair purposes were most common, and certain client demographics showed higher likelihoods of on-time payments.

## Remarks

- Lending decisions should be based on multiple parameters to mitigate losses from defaulters and ensure loans are extended to valid clients.
- Female working clients tend to make payments on time and may be given preference.
- Loans for repair purposes show higher on-time payment rates.
- Careful consideration should be given to clients seeking loans for third parties or refusing to disclose the loan purpose.
- Parameters such as credit amount, goods price, and client demographics like income and education level are indicative of loan default likelihood.
- Cross-verification of previous loan application data is crucial to assess the risk associated with lending to existing clients.

## Conclusion

This case study highlights the importance of data-driven decision-making in loan risk assessment. By leveraging EDA techniques, companies can identify key factors influencing loan default and tailor their lending strategies to minimize risk and maximize returns.
