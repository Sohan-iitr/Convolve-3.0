Convolve 3.0 (IIT Guwhati - ICICI Bank)

Introduction
Bank A issues Credit Cards to eligible customers. The Bank deploys advanced ML models and frameworks to decide on eligibility, limit, and interest rate assignment. The models and frameworks are optimized to manage early risk and ensure profitability. 
The Bank has now decided to build a robust risk management framework for its existing Credit Card customers, irrespective of when they were acquired. To enable this, the Bank has decided to create a “Behaviour Score”. A Behaviour Score is a predictive model. It is developed on a base of customers whose Credit Cards are open and are not past due. The model predicts the probability of customers defaulting on the Credit Cards going forward.
This model will then be used for several portfolio risk management activities.

Problem statement
Your objective is to develop the Behaviour Score for Bank A.

Datasets
You have been provided with a random sample of 96,806 Credit Card details in  “Dev_data_to_be_shared.zip”, along with a flag (bad_flag) – henceforth known as “development data”. This is a historical snapshot of the Credit Card portfolio of Bank A. Credit Cards that have actually defaulted have bad_flag = 1. You have also been provided with several independent variables. These include:
•	On us attributes like credit limit (varables with names starting with onus_attributes)
•	Transaction level attributes like number of transactions / rupee value transactions on various kinds of merchants (variables with names starting with transaction_attribute)
•	Bureau tradeline level attributes (like product holdings, historical delinquencies) – variables starting with bureau
•	Bureau enquiry level attributes (like PL enquiries in the last 3 months etc) – variables starting with bureau_enquiry
You have also been provided with another random sample of 41,792 Credit Card details in “validation_data_to_be_shared.zip” with the same set of input variables, but without “bad_flag”. This will be referred to going forward as “validation data”.
