# Market-Basket-Analysis-for-a-Supermarket
This repository contains a comprehensive Market Basket Analysis (MBA) on supermarket transaction data. The objective of this project is to uncover the associations and patterns between items frequently purchased together, providing insights that can be used to enhance sales strategies, optimize product placement, and improve inventory management.

**Market Basket Analysis**

Market Basket Analysis (MBA) is a data mining technique used in retail to uncover the associations and patterns between items purchased together. It helps in understanding customer purchasing behavior by identifying itemsets that frequently co-occur in transactions.


**Key Terms for Masket Basket Analysis:**

1. **Support**: Support is the frequency of an item/group of items divided by the total transactions. 
    Support (X) = Total number of transactions containing X/Total number of transactions


2. **Confidence**: It is the probability of people buying item B given they have bought item A.
      P(B|A) = P(A and B)/P(A)

3. **Lift**: Ratio of Confidence to Support gives the lift. 
* A lift value<1 means there is negative association between the antecendent and the consequent. 
* A lift value=1 means there is no association between the antecendent and the consequent. 
* A lift>1 means there is strong association between the antecendent and the consequent. 


The heat-maps/layouts of retail shops are designed keeping in mind the lift value.
