# Lending Club Case Study

Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.

If the factors for these risky loans can be identified, the lender can reject them, lowering the amount of credit loss.

**The objective of this case study is to identify such factors using EDA (Exploratory Data Analysis).**

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
When a person applies for a loan, there are two types of decisions that could be taken by the company(lender):

- Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

    - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

    - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

    - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

- Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Conclusions
The chances of getting a loan 'Charged Off' or 'default' increases with

- having a higher loan amount
- having a higher interest rate
- having loan grades in E,F or G
- borrower belonging to states like CA, NY and TX
- having a higher installment tenure
- having a purpose of 'small business' or 'credit card' payment


## Technologies Used
- Pandas - version 1.4.2
- Numpy - version 1.21.5
- Seaborn - version 0.11.2
- Matplotlib - version 3.5.1

## Acknowledgements
- This project was inspired by a case study from the Executive PG Programm in Machine Learning by IIIT Bengaluru 


## Contact
Created by [@rahulkpareek]