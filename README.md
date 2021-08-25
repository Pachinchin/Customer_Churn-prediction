# Customer_Churn-prediction
Data Dictionary  There are multiple variables in the dataset which can be cleanly divided in 3 categories:  

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
