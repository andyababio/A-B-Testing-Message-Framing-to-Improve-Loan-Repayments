## 🔄 Process Flow

◼ Data Preparation (Excel):
 - The raw retail data was cleaned and transformed in Microsoft Excel.  

◼ Data Modeling (Power BI):
 - The cleaned datasets were imported into Power BI for data modeling.

◼ Data Visualization & Analysis:
 - I then developed interactive visuals and KPIs in Power BI using **DAX** to highlight trends, relationships, and performance metrics.

---

## 🗂️ Dataset Overview

CUSTOMER
- customer_id (PK)
- full_name
- contact_number
- email
- gender

LOAN
- loan_id (PK)
- customer_id
- loan_amount
- loan_issue_date
- due_date
- current_dpd
- loan_size
- loan_status

CAMPAIGN
- campaign_id (PK)
- campaign_name
- start_date
- end_date
- channel
- test_type


MESSAGE_VARIANT
- variant_id (PK)
- campaign_id
- variant_type
- message_text

MESSAGE_LOG
- message_log_id (PK)
- customer_id
- loan_id
- variant_id
- date_sent
- delivery_status
- response_status

REPAYMENT
- repayment_id (PK)
- loan_id
- customer_id
- repayment_date
- repayment_amount
- repayment_type

Relevant relationships were then established between the above table to produce the following data model:
 <p align="center">
 <img alt="Data Model" src="Images/Data_model_marketing_analytics.png" width="60%" />
 </p>








