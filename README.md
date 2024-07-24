# Lending club case study
> A finance company specializing in providing various types of loans to urban customers wants develop a model to approve the loan based on the applicant’s profile. There are two types of risks are associated with the company's decision:
 - If the applicant is likely to repay the loan, not approving the loan results is a loss of business for the company.
 - If the applicant is likely to default on the loan, approving the loan may lead to a financial loss for the company.




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The primary objective is to analyze past loan applicant data to identify patterns that predict the likelihood of default. By understanding these patterns through Exploratory Data Analysis (EDA), the company aims to make informed decisions such as denying loans, reducing loan amounts, or lending to risky applicants at higher interest rates. This analysis will help Lending Club minimize financial losses and optimize their loan approval process.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Minor Impact
 - Higher loan amount (above 16K)
 - Higher installment amount (above 327)
 - Lower annual income (below 37K)
 - Higher debt to income ratio (above 15%)
 - Applicant’s address state (NV, SD, AK, FL, etc.)
 - Loan issue month (Dec, May, Sep)

### Heavy impact
 - Higher revolving line utilization rate (above 58%)
 - Repayment term (5 years)
 - Loan grade & sub-gr
 - Missing employment record
 - Loan purpose (small business, renewable energy, educational)
 - Derogatory public records (1 or 2)
 - Public bankruptcy records (1 or 2)

### Combined impact
 - High loan amount & interest rate for lower income group
 - High installment and longer repayment term
 - Home ownership (other) and loan purpose (car, moving or small business)
 - Residential state and loan purpose
 - Income group and loan purpose
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.7.6
- NumPy - version 1.18.1
- Pandas - version 1.2.3
- Matplotlib - version 3.1.3
- Seaborn - version 0.10.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was created as a case study required for Executive PG Programme in Machine Learning & AI - IIIT, Bangalore
- This project was based on [this tutorial]([https://www.example.com](https://jovian.com/vijay-grg/l)).


## Contact
Created by [@sreenivasam] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
