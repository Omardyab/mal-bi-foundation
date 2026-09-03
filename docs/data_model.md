# MAL BI Data Model
All data is synthetic. `customer_id` is the cross-domain join key.

Tables: customers, product_accounts, customer_activity, finance_transactions, credit_applications, credit_portfolio.

Certified Active Customer = unique customer with at least one Payment, Savings Deposit, Savings Withdrawal, or Credit Repayment in the trailing 30 days.
