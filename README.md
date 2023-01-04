# Lending Club Case Study

> Exploratory Data Analysis is done for a loan dataset that contains all the loans that were lent by a consumer finance company. EDA is used to understand how consumer attributes and loan attributes influence the tendency of the loan being default.

## Table of Contents

- [General Info](#general-information)
- [The Problem](#the-problem)
- [Solution](#solution)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Contributors](#contributors)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### The problem

When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

### Solution

Performing EDA on the dataset and understanding how each of the attributes behave will help the company in reducing the risk of any loss.

#### Process followed:

1. Data Pre-processing <br>
   > - Fixing missing values
   > - Standardizing values
   > - Filtering data
   > - Deriving metrics
2. Data Analysis
   > - Univariate Analysis
   > - Segmented Univariate Analysis
   > - Bivariate Analysis
3. Conclusions from the Data Analysis

### The Dataset

The [dataset](https://github.com/kunal449/LendingClubCaseStudy/tree/main/data/loan) used in this project contains information about past loan applicants and if they 'defaulted' or not.

## Recommendations
Borrowers with Lower Income should be provided loans considering

A. Loan amount should be based on interest rates, term, installments, dti and delinq history so that

 a. loan amount should not be too high  [possible loss of business but Risky]
 b. OR the installments are payable by the borrower
B. should be reviewd for DTI, delinq history, revolving util and inquiries for credit on a regular basis

Different Loan purposes have different behavior and they should be evaluated based on

A. Annual Income, Credit history (DTI, revol_util, delinq, credit_inquiries and public records), Borrower specific information (Borrowers State, employment length), Loan Grade

Different Loan purposes have different behavior and they should be evaluated based on

A. Annual Income, Credit history (DTI, revol_util, delinq, credit_inquiries and public records), Borrower specific information (Borrowers State, employment length), Loan Grade

Verifications ie both ‘Verification’ & ‘Source Verification’need some more improvements as the default rate is still high.

A. Considering that verifications may have done in the cases of risky loans and those cases may have been addressed for the involved Risk, either by increasing the interest rates / reduing loan amount / adjusting the term, these adjustments needs a review whether the risk is getting mitigated. As we still see the defaults in these scenarios. 
High Risk loan can be reduced on by

A. Reducing loan amount / adjusting the installment, interest rate and term to compensate the risk
B. asking for co-borrowers / collateral
C. getting Investors / Credit Default Swaps

## Technologies Used

- NumPy
- Pandas
- Matplotlib
- Seaborn

## References : 
https://www.lendingclub.com/ <br/>
https://www.lendingclub.com/foliofn/rateDetail.actio

## Acknowledgements

This case study was done as part of the Statistics Essentials Module of the Executive PG Programme in Machine Learning & AI - November 2022 - IIIT, Bangalore & Upgrad.

## Contributors

- Prasanna Rahavendra A
- Kunal Mahale
