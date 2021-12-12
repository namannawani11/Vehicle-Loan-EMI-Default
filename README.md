# Vehicle-Loan-EMI-Default
Predict the probability of a borrower defaulting on a vehicle loan in the first EMI on the due Date. So that financial firm can focus on those clients which can default and avoid losses in Business.



Variable Name	-------------Description	


UniqueID----------------- 	Identifier for customers	

loan_default	-------------Payment default in the first EMI on due date	

disbursed_amount-----------Amount of Loan disbursed	

asset_cost-----------------Cost of the Asset	

ltv	Loan to Value of the asset	

branch_id	Branch-----------where the loan was disbursed	

supplier_id----------------Vehicle Dealer where the loan was disbursed	

manufacturer_id------------Vehicle manufacturer(Hero, Honda, TVS etc.)	

Current_pincode------------Current pincode of the customer	

Date.of.Birth--------------Date of birth of the customer	

Employment.Type-----------Employment Type of the customer (Salaried/Self Employed)	

DisbursalDate-------------Date of disbursement	

State_ID------------------State of disbursement	

Employee_code_ID----------Employee of the organization who logged the disbursement	

MobileNo_Avl_Flag---------if Mobile no. was shared by the customer then flagged as 1	

Aadhar_flag---------------if aadhar was shared by the customer then flagged as 1	

PAN_flag------------------if pan was shared by the customer then flagged as 1	

VoterID_flag--------------if voter  was shared by the customer then flagged as 1	

Driving_flag-------------	if DL was shared by the customer then flagged as 1	

Passport_flag------------	if passport was shared by the customer then flagged as 1	

PERFORM_CNS.SCORE---------Bureau Score	

PERFORM_CNS.SCORE.DESCRIPTION-----	Bureau score description	
PRI.NO.OF.ACCTS-----------count of total loans taken by the customer at the time of disbursement	Primary accounts are those which the customer has taken for his personal use

PRI.ACTIVE.ACCTS----------count of active loans taken by the customer at the time of disbursement	

PRI.OVERDUE.ACCTS---------count of default accounts at the time of disbursement	

PRI.CURRENT.BALANCE-------total Principal outstanding amount of the active loans at the time of disbursement	

PRI.SANCTIONED.AMOUNT-----total amount that was sanctioned for all the loans at the time of disbursement


PRI.DISBURSED.AMOUNT-------total amount that was disbursed for all the loans at the time of disbursement	

SEC.NO.OF.ACCTS------------count of total loans taken by the customer at the time of disbursement	Secondary accounts are those which the customer act as a co-applicant or gaurantor

SEC.ACTIVE.ACCTS-----------count of active loans taken by the customer at the time of disbursement	

SEC.OVERDUE.ACCTS----------count of default accounts at the time of disbursement

SEC.CURRENT.BALANCE--------total Principal outstanding amount of the active loans at the time of disbursement	

SEC.SANCTIONED.AMOUNT------total amount that was sanctioned for all the loans at the time of disbursement	

SEC.DISBURSED.AMOUNT-------total amount that was disbursed for all the loans at the time of disbursement	

PRIMARY.INSTAL.AMT---------EMI Amount of the primary loan	

SEC.INSTAL.AMT-------------EMI Amount of the secondary loan	

NEW.ACCTS.IN.LAST.SIX.MONTHS----	New loans taken by the customer in last 6 months before the disbursment	

DELINQUENT.ACCTS.IN.LAST.SIX.MONTHS-----	Loans defaulted in the last 6 months	

AVERAGE.ACCT.AGE---------- Average loan tenure	

CREDIT.HISTORY.LENGTH------Time since first loan	
NO.OF_INQUIRIES	------------Enquries done by the customer for loans	

