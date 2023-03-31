# Loan-Approval-System				
Evaluate customer's loan request by using classification method -

ATA Bank Loan Approval Method- how to prepare dataset.

Features(8) -

(1)Age = if applicant's age is older than 60, change 0 else 1# 

(2)Dependents = if applicant has more than 3 dependents in his family, change to 0 else 1# 

(3)Education = if he is graduated, change to 2, else 1# 

(4)Income = if income is <= 10000, 1 And <= 20000, 2 else 3# 

(5)LoanAmount = loan is <= 100000, 1 And <= 200000, 2 else 3# 

(6)Loan_Amount_Term = loan term is <= 120, 1 And <= 240, 2 else 3# 

(7)Credit_History = no history= 0, has history=1# 

(8)Property_Area = Area 1=1, Area2=2, Area3=3.

Target -

Loan_Status = add all 8 features and if the value is > 12, Yes else No# 

True Positive  - ATA bank approves loan request but system also agree# 

False Positive - System approves loan request but ATA bank did not allow.

True Negative  - ATA bank did not approves loan request but system also agree# 

False Negative - System rejects loan request but ATA allows that loan request# 

Python Coding

1-Read dataset
Rows =3543 #
No    1922
Yes   1621.

2-Split into train size=70% and test size=30%.
3-KNN classifier.

4-Logistic Regression.

5-SVC

Linear Kernel#	

Poly Kernel#	

Gaussian#

Correlation by Logistic Regression for testing.
