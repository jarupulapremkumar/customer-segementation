# Customer-segementation
### Summary:
  - Marketing is crucial for the growth and sustainability of any business.
   ![image](https://user-images.githubusercontent.com/46964929/180448058-ff020344-4aed-47f3-bcab-2ba678162b0f.png)
  - One of the key pain points for marketers is to know their customers and identify their needs.
  -  One of the key pain points for marketers is to know their customers and identify their needs.
  -  If data about the customers is available, data science can be applied to perform market segmentation. 
### Objective:
  -  In this case study, you have been hired as a consultant to a bank in New York City. 
  -  The bank has extensive data on their customers for the past 6 months. 
  -  The marketing team at the bank wants to launch a targeted ad marketing campaign by dividing their customers into at least 3 distinctive groups
### About The Dataset:
  - The marketing team at the bank wants to launch a targeted ad marketing campaign by dividing their customers into at least 3 distinctive groups.  
  - # CUSTID: Identification of Credit Card holder 
  - # BALANCE: Balance amount left in customer's account to make purchases
  - # BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
  - # PURCHASES: Amount of purchases made from account
  - # ONEOFFPURCHASES: Maximum purchase amount done in one-go
  - # INSTALLMENTS_PURCHASES: Amount of purchase done in installment
  - # CASH_ADVANCE: Cash in advance given by the user
  - # PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
  - # PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
  - # ONEOFF_PURCHASES_FREQUENCY: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
  - # PURCHASES_INSTALLMENTS_FREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
  - # CASH_ADVANCE_FREQUENCY: How frequently the cash in advance being paid
  - # CASH_ADVANCE_TRX: Number of Transactions made with "Cash in Advance"
  - # PURCHASES_TRX: Number of purchase transactions made
  - # CREDIT_LIMIT: Limit of Credit Card for user
  - # PAYMENTS: Amount of Payment done by user
  - # MINIMUM_PAYMENTS: Minimum amount of payments made by user  
  - # PRC_FULL_PAYMENT: Percent of full payment paid by user
  - # TENURE: Tenure of credit card service for user
### Algorithms Used :
  **K-Means**
    ![image](https://user-images.githubusercontent.com/46964929/180449750-a1475d78-d946-41a4-bac0-dddf9a01a9ef.png)
   - Kmeans is used for clustering the customers into different clusters

  **PCA (pricipal component analysis)**:
    - Using PCA for Dimensionality reduction and then Using Kmeans on that data for clustering
     ![image](https://user-images.githubusercontent.com/46964929/180451445-cbf88934-d0aa-4223-a6d4-5ea0dd859e49.png)

   **AutoEncoder:**
    - Since PCA is Linear Transformation Dimensionality reduction it is not suitable for non-linear data for that purpose we use deep learning Autoencoders for encoding non linear dataset.
    - We use Autoencoder for Dimensionality Reduction and then we use Kmeans for clustering that data also.
    ![image](https://user-images.githubusercontent.com/46964929/180451736-cb53e57f-0a62-4522-b640-9f581064fc9b.png)

    
 ### Outcome :
    - We Then assign the applicable cluster to the customers then using that data we can target the applicable customers with Ads or Offers
    ![image](https://user-images.githubusercontent.com/46964929/180451829-0d7d3db7-e154-46f9-bf5e-0225238a839d.png)

   






