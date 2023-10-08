# Project Name: Lending Club Case Study
> The case study is based on a consumer finance company. The company specializes in lending different types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
The data shared by UpGrad contains the information about past loan applicants and whether they ‘defaulted’ or not.
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

# Problem Statement: Lending Club Case Study
>When a person applies for a loan, there are two types of decisions that could be taken by the company:
(1) Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
1.1 Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
1.2 Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
1.3 Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
(2) Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
>Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. 
> In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
>The business objective  is to identify risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Small Business Applicants have high chances of getting charged off.    
- Charged off proportion increases with grades moving from “A” towards “G”.
- Charged off proportion increases as Interest Rate Increases.
- Higher the public bankruptcy record greater the charged-off proportion.		
- The loan amounts are bigger on average for small business purpose among all purposes of Loan.
- Those who already have Derogatory Public Records have higher charged off chances than others.
- Average interest rate is considerably higher for 60 months loan term than 36 months.
- Ones getting charged off have lower annual incomes than the ones who has fully paid for each and every grade.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [VishalArora1211@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->