# Project - Lending Club Case Study
> In this case study, we are presented with loan paid and defaulted dataset. Using this dataset, our objective is to identify key variables that impact loan default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project is related to risk analysis for loan applicants
- In loan approval/reject decisions, the first information than a loan operating agent would need is if the applicant shows certain red flags
- In our EDA, we will identify certain drivers which will enable a loan evaluator to assess the probablilty of risk for a loan applicant
- Lending Case Study dataset is used as provided by UpGrad Team


## Conclusions
Loan Amount and Interest Rate Charged – If the loan amount is greater than 25,000, indicates a 20%-25% probability of default based on historical data. The profile become more risky if interest rate charged exceeds 15%.

Loan Term – 60 months loan term is more likely to not be paid compared with 36 months. It also has a correlation with point loan amount.

Loan Purpose – Small Business and Renewable energy related purposes tend to have more than 20% default rate. This is followed up by loans taken for education or higher studies.

Public Records – Applicants with one or more public records need to be closely verified since they have higher defaults than candidates with no public records.

State Address – Data provides that applicants from NE state have a whopping 60% default rate. So, a loan approver needs to be careful with applicants filing from that state.

Loan Grade – More the loan grade, higher the probability of defaulting. This is also observed in sub grade columns of Grade.

DTI – The debt to income ratio is also an important variable. Higher the ratio, more is the chance of defaulting.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy, pandas, matplotlib, seaborn and plotly libraries used
- Jupyter notebook is used for python programming

