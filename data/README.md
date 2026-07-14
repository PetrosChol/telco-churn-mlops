# Data

Raw data is not committed to keep the repo light and licenses clean.

## Download

Telco Customer Churn (https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Dictionary
| Column | Type | Description |
|---|---|---|
| customerID | object | Unique identifier for each customer |
| gender | object | Customer's gender (`Female`, `Male`) |
| SeniorCitizen | int64 | Whether the customer is a senior citizen (`0` = No, `1` = Yes) |
| Partner | object | Whether the customer has a partner (`Yes`, `No`) |
| Dependents | object | Whether the customer has dependents (`Yes`, `No`) |
| tenure | int64 | Number of months the customer has stayed with the company |
| PhoneService | object | Whether the customer has phone service (`Yes`, `No`) |
| MultipleLines | object | Whether the customer has multiple lines (`Yes`, `No`, `No phone service`) |
| InternetService | object | Customer's internet service provider (`DSL`, `Fiber optic`, `No`) |
| OnlineSecurity | object | Whether the customer has online security add-on (`Yes`, `No`, `No internet service`) |
| OnlineBackup | object | Whether the customer has online backup add-on (`Yes`, `No`, `No internet service`) |
| DeviceProtection | object | Whether the customer has device protection add-on (`Yes`, `No`, `No internet service`) |
| TechSupport | object | Whether the customer has tech support add-on (`Yes`, `No`, `No internet service`) |
| StreamingTV | object | Whether the customer has streaming TV add-on (`Yes`, `No`, `No internet service`) |
| StreamingMovies | object | Whether the customer has streaming movies add-on (`Yes`, `No`, `No internet service`) |
| Contract | object | Contract term (`Month-to-month`, `One year`, `Two year`) |
| PaperlessBilling | object | Whether the customer uses paperless billing (`Yes`, `No`) |
| PaymentMethod | object | Payment method (`Electronic check`, `Mailed check`, `Bank transfer (automatic)`, `Credit card (automatic)`) |
| MonthlyCharges | float64 | Amount charged to the customer monthly |
| TotalCharges | object | Total amount charged to the customer; stored as string and needs numeric conversion — 11 rows with `tenure == 0` have a blank value here |
| Churn | object | Target variable: whether the customer churned (`Yes`, `No`) |
