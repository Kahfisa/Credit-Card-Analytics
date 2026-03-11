# Credit-Card-Report


## Introduction
Financial institutions generate large volumes of customer and transaction data every day, but turning this data into meaningful insights remains a challenge. Therefore, this project aims to analyze customer demographics, revenue contribution, and credit risk using Python for data processing and Looker Studio for visualization to support data-driven decision making.

## Tools
- Python
- Looker Studio

## Dataset
|Dataset              |Column                                       |Description                                                      |
|---------------------|---------------------------------------------|-----------------------------------------------------------------|
|credit card          |client_num                                   |Unique customer identification number.
|                     |customer_age                                 |Customers age.
|                     |gender                                       |Customers gender.
|                     |dependent_count                              |Number of dependents of the customer.
|                     |education_level                              |Customers education level.
|                     |marital_status                               |Customers marital status.
|                     |state_cd                                     |State or region where the customer resides.
|                     |zipcode                                      |Postal code of the customer's residence.
|                     |car_owner                                    |Indicates whether the customer owns a car.
|                     |house_owner                                  |Indicates whether the customer owns a house.
|                     |personal_loan                                |Indicates whether the customer has a personal loan.
|                     |contact                                      |Primary contact method of the customer.
|                     |customer_job                                 |Customers occupation.
|                     |income                                       |Customers income..
|                     |cust_satisfaction_score                      |Customer satisfaction score with the bank or credit card services.
|                     |card_category                                |Type of credit card owned by the customer.
|                     |annual_fees                                  |Annual fees charged for the credit card.
|                     |activation_30_days                           |Indicator of whether the card was activated within 30 days after issuance.
|                     |customer_acq_cost                            |Customer acquisition cost.
|                     |week_start_date                              |Start date of the week for the transaction or observation period.
|                     |week_num                                     |Week number in the year.
|                     |qtr                                          |Quarter of the year (1–4).
|                     |current_year                                 |Year when the data was recorded.
|                     |credit_limit                                 |Maximum credit limit granted to the customer.
|                     |total_revolving_ba                           |Total transaction value conducted by the customer during a specific period.
|                     |total_trans_amt                              |Total number of transactions during a specific period.
|                     |total_trans_vol                              |Total number of transactions during a specific period.
|                     |avg_utilization_ratio                        |Average credit utilization ratio.
|                     |use_chip                                     |Indicates whether transactions used the card chip.
|                     |exp_type                                     |Type of credit card, specifying what the card can be used
|                     |interested_earned                            |Interest earned by the customer.
|                     |deliquent_acc                                |Number of delinquent accounts or late payments.

## Business Question
- How are customers distributed by occupation, marital status, and geographic location?
- Which occupation and card types contribute most to total revenue (annual fees)?
- How do average transaction volumes differ across customers occupation?
- Which occupation has the highest average card utilization ratio?
- Which occupations have the highest number of delinquent accounts?
- Which states show higher delinquency accounts?

## Dashboard Preview

<img width="1365" height="948" alt="image" src="https://github.com/user-attachments/assets/5508c275-d818-4cdd-a6c1-9c6cec378562" />

<img width="1367" height="948" alt="image" src="https://github.com/user-attachments/assets/bf874603-fd64-45e1-928f-9a8ce5e52953" />

<img width="1367" height="948" alt="image" src="https://github.com/user-attachments/assets/b71e3940-658b-4fa0-989c-0e946fb6da4c" />


Logo Source: Logo by juicy_fish on Freepik


## Insight
- The majority of credit card users come from the self-employed segment, followed by businessmen and white-collar workers, with most being married. Geographically, the highest concentration of customers is found in New York, California, Texas, and Florida, indicating a strong credit card market focus in these regions.
- The self-employed segment is the main contributor to annual fee revenue, primarily through the Blue Card category, with total revenue reaching 353,340. Meanwhile, in terms of transaction-based revenue, the businessman segment shows the highest potential, with an average of 80 transactions during the credit card usage period, indicating more intensive card usage.
- The highest default rates are observed in New York, California, Texas, and Florida, indicating a significant concentration of credit risk in regions with high economic activity. From a customer profile perspective, individuals with a Graduate-level education and occupations as Self-employed, Businessmen, and White-collar workers exhibit the highest delinquency rates, highlighting the need for targeted attention to these segments in credit risk management.
