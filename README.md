# L&T Financial Services-Data-Science-FinHack
 In this FinHack, you will develop a model for our most common but real challenge ‘Loan Default Prediction’ 

# Problem Statement
# Vehicle Loan Default Prediction
Financial institutions incur significant losses due to the default of vehicle loans. This has led to the tightening up of vehicle loan underwriting and increased vehicle loan rejection rates. The need for a better credit risk scoring model is also raised by these institutions. This warrants a study to estimate the determinants of vehicle loan default. A financial institution has hired you to accurately predict the probability of loanee/borrower defaulting on a vehicle loan in the first EMI (Equated Monthly Instalments) on the due date. Following Information regarding the loan and loanee are provided in the datasets:

Loanee Information (Demographic data like age, income, Identity proof etc.)
Loan Information (Disbursal details, amount, EMI, loan to value ratio etc.)
Bureau data & history (Bureau score, number of active accounts, the status of other loans, credit history etc.)
Doing so will ensure that clients capable of repayment are not rejected and important determinants can be identified which can be further used for minimising the default rates.

## Data Description
1. train.zip: contains train.csv and data_dictionary.csv.
2. train.csv: contains the training data with details on loan as described in the last section
3. data_dictionary.csv: contains a brief description on each variable provided in the training and test set.
4. test.csv: contains details of all customers and loans for which the participants are to submit probability of default.
5. sample_submission.csv: contains the submission format for the predictions against the test set. A single csv needs to be submitted as a solution.

## Evaluation Metric
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

## Public and Private Split
Test data is further randomly divided into Public (25%) and Private (75%) data. Your initial responses will be checked and scored on the Public data. The final rankings would be based on your private score which will be published once the competition is over.
