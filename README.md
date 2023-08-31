# [POWER BI] Customer_Churn_Analysis_PowerBI_Project

## I. Introduction
### 1. Introduction to Dataset
* Dataset: **OS Collection Performance**
* The dataset includes one table containing information on debt collection by partners, organized by month for the years 2020 and 2021.
### 2. Data Dictionary
![image](https://github.com/leanhkienn/Customer_Churn_Analysis_PowerBI_Project/assets/116093407/f1191f9d-6514-421a-8e84-4fd376bc76a4)

### 3. Business Questions
* Which partners are the most efficient at debt recovery, and what factors contribute to their success?
* How can the Head of Finance at Bank X optimize the allocation of the debt portfolio to maximize profits and minimize risk?
* What strategies can the Head of Collection at Bank X implement to improve debt recovery rates and enhance cooperation with its partners?

## III. Visualization
### 1. Overview
![image](https://user-images.githubusercontent.com/101726623/235464138-e572d91d-5ee7-4a76-bf5b-3e8639634920.png)

### 2. Debt Profile
![image](https://user-images.githubusercontent.com/101726623/235464239-5d32608f-7288-4703-b785-4c087e46d22a.png)

### 3. (Insights) Effective debt recovery
![image](https://user-images.githubusercontent.com/101726623/235464301-a9c14a21-8c8d-485b-815b-b8248cae828c.png)

## IV. Insights
1, In terms of total collection
* ASA, HMK, GLX, NDC, TCG are the top companies with a lot of debt.
* BFC, FBI, TDO companies collect the least amount of debt.

2, In terms of Range_DPD
* Mid-term: the companies with the highest total collection are: ASA> HMK>NDC>TCG>GLX
* Long-term: the companies with the highest total collection are: GLX>HMK>ASA>NDC>TCG
* Short-term: the companies with the highest total collection are: GLX>HMK>ASA>TCG>NDC
* Deadloan: the companies with the highest total collection are: NDC>FBI>GLX>ASA

3, In terms of Recovery rate
* The top companies with high revocery rates are: AMG>FBI>DK>HMK ., respectively.

4, Customers have a high demand for mid-term loans 37.79%, then short-term: 28.49%, long-term: 20.82%.

5, Short-term is the easiest loan to claim (the highest recovery rate).

6, In contrast, Long-term has the lowest return rate.

7, Deadloan has the highest loan ratio: unsecured Loan, Secured Loan, Credit Card.

## V. Recommendations

1, If you want to collect a lot of debt (total collected):
Debt allocation according to loan term to OS_company
* Long-term: ASA, HMK, NDC
* Mid-term: ASA, GLX, NDC
* Short-term: GLX, ASA, HMK
* Deadloan: NDC, FBI, GLX

2, If you want a high recovery_rate
Debt allocation by loan term to OS_company Long-term: TDO Mid-term: FBI, NDC
* Short-term: AMG (super high claim rate 82.43%), FBI, NDC
* Deadloan: HMK, NDC

3, It is necessary to consider whether the following companies should cooperate in the future because of the inefficient debt collection index: DK, HNA, BFC.

4, NDC is a company that handles debts well: like Deadloan vs other of Product_final.

5, Deadloan accounts have a high payout ratio in the last months of the year 10, 11, 12.

6, December is the month with the highest repayment rate of the year, then it drops to the lowest in February.

7, The bank should expand and promote the Mid-term loan package because it has the highest recovery rate.
