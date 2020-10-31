# Customer Segmentation Credit Card User

### Business Understanding
* Theme:
Customer segmentation of credit card customers

* Problem:
The company wants to make the right marketing strategy according to the conditions of its customers.

* Destination:
Creating customer segmentation so that credit card companies can create appropriate marketing strategies for each group of customers.

* Question:
What is the right customer segmentation based on available credit card customer information?

* Analytic approach:
Clustering

* Data Requirements:
Payment activity, balance amount and credit card limit

*Solution Needs:
The need to segment customers for marketing strategies

* Output:
Customer segmentation based on customer credit card activity and specifications

### Data Source and Dictionary
The dataset was obtained from Kaggle (https://www.kaggle.com/arjunbhasin2013/ccdata). The dataset contains the activity of 9000 active credit card customers for 6 months. There are 18 columns used to describe information, activities and types of customers.

1. CUSTID : No identifikasi pemegang kartu kredit
2. BALANCE : The remaining balance to make a purchase
3. BALANCEFREQUENCY : Frequency of balance change, score between 0 and 1 (0 = infrequent, 1 = frequent)
4. PURCHASES : Purchase amount
5. ONEOFFPURCHASES : Maximum purchase in a transaction
6. INSTALLMENTSPURCHASES : Number of purchases during installment
7. CASHADVANCE : Cash in advance given by the user
8. PURCHASESFREQUENCY : How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
9. ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
10. PURCHASESINSTALLMENTSFREQUENCY : How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
11. CASHADVANCEFREQUENCY : How frequently the cash in advance being paid
12. CASHADVANCETRX : Number of Transactions made with "Cash in Advanced"
13. PURCHASESTRX : Numbe of purchase transactions made
14. CREDITLIMIT : Limit of Credit Card for user
15. PAYMENTS : Amount of Payment done by user
16. MINIMUM_PAYMENTS : Minimum amount of payments made by user
17. PRCFULLPAYMENT : Percent of full payment paid by user
18. TENURE : Tenure of credit card service for user
