# CreditCard
## Goal
This project is to develop a customer segamentation for marketing strategies-Customer-Segmentation
## Data Information
|| **Variable**    | **Description** |
|:---| :---        |    :---     |
|1| CUST_ID | Identification of Credit Card holder (Categorical) |
|2| BALANCE | Balance amount left in their account to make purchases |
|3| BALANCE_FREQUENCY | How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated) |
|4| PURCHASES | Amount of purchases made from account |
|5| ONEOFF_PURCHASES | Maximum purchase amount done in one-go |
|6| INSTALLMENTS_PURCHASES | Amount of purchase done in installment |
|7| CASH_ADVANCE | Cash in advance given by the user |
|8| PURCHASES_FREQUENCY | How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased) |
|9| ONEOFF_PURCHASES_FREQUENCY | How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased) |
|10| PURCHASES_INSTALLMENTS_FREQUENCY | How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done) |
|11| CASH_ADVANCE_FREQUENCY | How frequently the cash in advance being paid |
|12| CASHADVANCE_TRX | Number of Transactions made with "Cash in Advanced" |
|13| PURCHASES_TRX | Number of purchase transactions made |
|14| CREDIT_LIMIT | Limit of Credit Card for user |
|15| PAYMENTS | Amount of Payment done by user | 
|16| MINIMUM_PAYMENTS | Minimum amount of payments made by user |
|17| PRC_FULL_PAYMENT | Percent of full payment paid by user |
|18| TENURE | Tenure of credit card service for user |

## Customer Segmentation Result
| **Attributes** | **C0 Cluster** | **C1 Cluster** | **C2 Cluster** | **C3 Cluster** | **C4 Cluster** |
|:---|:--- |:---|:---|:---|:---|
| PURCHASES |||low|||
| ONEOFF_PURCHASES |low||low|||
| INSTALLMENTS_PURCHASES |||low|low||
| CASH_ADVANCE |low|||low|low|

|**Customer Clusters**|**Behavior Description**|
|:---|:--- |
|Cluster 0|Purchase with installments with using cash in advance|
|Cluster 1|Have all behaviors with their credit cards|
|Cluster 2|Have low amount of purchases but purchase with cash in advance |
|Cluster 3|Have high amount of purchases and mostly pay in one-off|
|Cluster 4|Purchase without using cash in advance|
