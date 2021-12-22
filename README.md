# RWD-drug-efficacy

#### Brief Summary Objective:
To rebalance dataset so that confounding factors are removed and drug type A vs B can be compared fairly. 

#### Method to rebalance dataset: 
A balanced have simillar profies of people drug type cannot be predicted accurately from patient profile. Hence built a decision tree classifier to profile patients and subsampled equal number of patients taking drugA/B from each terminal node of decision tree. 

#### Results
Used a univaraite KM estimator and log rank test on balanced dataset to determine efficacy. No difference in efficacy for both drugs.
