# RWD-drug-efficacy

#### Brief Summary Objective:
To rebalance dataset so that confounding factors are removed and drug type A vs B can be compared fairly. 

#### Method to rebalance dataset: 
A balanced have similar profiles of people for each drug type, hence drug type cannot be predicted accurately from patient profile. Hence built a decision tree classifier to profile patients and subsampled an equal number of patients taking drugA/B from each terminal node of the decision tree. 

#### Results
Used a univariate KM estimator and log rank test on the balanced dataset to determine efficacy. No difference in efficacy for both drugs.
