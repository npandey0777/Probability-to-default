# Probability-to-default
## Problem Statement: 
The business is interested to know which customers are more likely to miss the payment of their EMIs so that
they can plan proper strategy to tackle them.

## ML Statetment:
The customer's probabilty to default(miss)EMI next month  needs to be calculated.
Based on their probablity they were segmented in four category- VERY HIGH, HIGH , MEDIUM and LOW risky customers.

## Approach

Different features are created based on Customers payment behaviour, demography and bounce patterns.
Weight of evidence (WoE) is used for feature importance. 
Boosting and Bagging are used to train the model and get probability of default.
Subsequently, Deciles are created and divided into four categories of RISK 


