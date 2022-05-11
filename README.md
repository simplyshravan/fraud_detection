# Lending Club Case Study
> Lending Club receives a lot of loan application. The company has to make a decision for loan approval based on applicant's profile. This project focusses on indetifying the keys factors to take that decision.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contributors](#contributors)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.
- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment.
- Data set used is [DataSet](https://github.com/simplyshravan/fraud_detection/blob/master/ml_model.py)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. LC should reduce the rate of interest for 60 months tenure to borrowers as the chance for them to default is more.
2. Grade is a good attribute in detecting the defaulters. LC should be more careful for borrowers having grade G to A.
3. LC should avoid giving loans to states ID, NV and NE.
4. Loan for the purpose of small businesses are likely to default the loan. LC should reduce approving loan to them.
5. LC should look into the annual income of the borrower. Borrowers with less annual income are likely to default the loan.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python Pandas - version 1.1.5
- Python Numpy - version 1.19.5
- Python Seaborn - version 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contributors
* [Shubhada](https://github.com/Shubhada-11)
* [Shravan](https://github.com/simplyshravan)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
