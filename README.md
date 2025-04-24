# Problem 
## 🧠 Customer Churn Prediction for Retail Banking

The goal of this project is to **predict customer churn** for a retail bank using a combination of **demographic**, **relationship**, and **transactional** data.

Churn is defined as customers whose **average balance in the next quarter falls below the minimum threshold**, indicating a potential disengagement or exit from the bank.

---

### 🎯 Objectives

The bank seeks to proactively identify **at-risk customers** by analyzing patterns such as:

- 📉 Declining account activity or balance trends  
- 🔄 Irregular transaction behavior  
- 👥 Demographic segments more prone to churn (e.g., age, occupation, dependents)  
- 💸 Changes in credit and debit volume  

---

### 🎯 Benefits of Prediction

By accurately predicting churn, the bank can:

- 🎯 Launch targeted **retention strategies** (e.g., promotions or relationship management)
- 🤝 Personalize **customer engagement**
- 💰 Reduce **revenue loss** from dormant or closing accounts

---

### 🧾 Features Used

The model leverages a rich set of features from multiple dimensions:

#### 👤 Customer Demographics
- Age  
- Gender  
- City  
- Occupation  
- Number of Dependents  
- Vintage (relationship length with bank)  

#### 🏦 Bank Relationship Metrics
- Net worth category  
- Branch code  
- Days since last transaction  

#### 💳 Transactional Trends
- Current and previous balances  
- Monthly average balances (current and past quarters)  
- Credit and debit amounts (current and previous months)  
- Balance volatility and transaction frequency  



# Customer_Churn-prediction Data Dictionary  
There are multiple variables in the dataset which can be cleanly divided in 3 categories:  

### Demographic information about customers  
Customer_id         - Customer id  
vintage             - Vintage of the customer with the bank in number of days\
Age                 - Age of customer
Gender              - Gender of customer
Dependents          - Number of dependents
Occupation                            - Occupation of the customer
City                                - City of customer (anonymised
### Customer Bank Relationship 
Customer_nw_category                -Net worth of customer (3:Low 2:Medium 1:High)  
Branch_code                         - Branch Code for customer account  
Days_since_last_transaction         - No of Days Since Last Credit in Last 1 year
### Transactional Information  
Current_balance                   -Balance as of today
Previous_month_end_balance        - End of Month Balance of previous month
Average_monthly_balance_prev      - Average monthly balances (AMB) in Previous Quarter
Average_monthly_balance_prevQ2    - Average monthly balances (AMB) in previous to previous quarter 
Current_month_credit              - Total Credit Amount current month  
Previous_month_credit             - Total Credit Amount previous month  &lt;b>current_month_debit&lt;/b> - Total Debit Amount current month  
Previous_month_debit              -Total Debit Amount previous month  
Current_month_balance             - Average Balance of current month 
Previous_month_balance            -Average Balance of previous month 
Churn&lt;/b>                      - Average balance of customer falls below minimum balance in the next quarter (1/0)

### Outcome 
Here, we can see that the model based on RFE is giving the best result for each fold and students are encouraged to try more feature selection techniques and fine tune to get the best results.



<img width="541" alt="Screenshot 2025-04-24 at 09 58 03" src="https://github.com/user-attachments/assets/0a53e32b-eba2-4311-ba0f-6fd0a08b1d27" />



