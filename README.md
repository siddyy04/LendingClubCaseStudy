# Lending Club Case Study
> The business problem is for a consumer finance company which specialises in giving out various types of loans to urban customers. When the company receives a loan application, it has to make a decision for loan approval based on the applicant’s profile.

We have been provided the historical data for loan applications that were approved by the company after analysing the associated business risks and whether the borrowers defaulted or not.

Our aim is to identify, using EDA, the strong variables which indicate whether a borrower is likely to default. This will be used for taking actions such as denying the loan, reducing the amount of loan, lending at competitive interest rates or at a higher interest rate (for risky applicants), etc. and hence reduce credit loss for the company.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- This project is meant to understand, using EDA, the strong variables which indicate whether a borrower is likely to default on a loan. This will be used for taking actions such as denying the loan, reducing the amount of loan, lending at competitive interest rates or at a higher interest rate (for risky applicants), etc. and hence reduce credit loss for the company.
- This project is a graded assignment under the EDA module of Upgrad and IIITB's Executive PG Program in ML & AI
- The business problem is for a consumer finance company which specialises in giving out various types of loans to urban customers. When the company receives a loan application, it has to make a decision for loan approval based on the applicant’s profile.
- We have been provided the historical data for loan applications that were approved by the company after analysing the associated business risks and whether the borrowers defaulted or not.



## Conclusions
- Though a greater number of loans are applied for 36 months (about 3 years) and have more defaulters, the ratio of charged off loan is more for 60 months (about 5 years).
- The chance of default is monotonically increasing with the interest rate i.e., the high the interest rate high the default rate chances. Interest rate is high for lower grades. So, there is possibility of more charged off for them.
- The ratio of defaulters is maximum for small scale business borrowers; however, the numbers are high for debt consolidation
- Defaulter chance is inversely proportional to the annual income. High the income less chance of default.
- Default chances is increasing with the increase in the debt-to-income ratio.
- Default chances is directly proportional to the loan amount. Also, chances of default is more when the home ownership is ‘other’.
- From analysis it’s confirm that chances of default is high when purpose is ‘small business’ and the term is 36 months (about 3 years). Also, for 60-month term the default chances is high when purposes are debt consolidation, educational, house, other, small business and the vacation purposes.
- Trend shows that default chances are more when the home ownership status is ‘other’, and the term is 60-month period. Even when the term is 36-month period, the default chances are the high if the home ownership status is other. But there is only one entry (term = 60-month period and home ownership = other), and very less data points in the ‘other’ home ownership. So, it is better to avoid the loans when the home ownership is others.
- In general, educational, house, other and the small business loans are having very high interest rate, debt consolidation with medium high interest rate and renewal energy, house with high interest rate are showing more chances of default .
- The high-income group for all purpose is relatively safe to lend money. The small business is showing high default chances in all income group except very high-income group. Loan with purpose renewal energy is showing high chance of default with very low income, low income, and high-income bracket.
- Loan with purpose car, credit card, home improvement, medical and wedding is showing less chances of default among various category and one of the safest purpose to lend. On the other hand, loan with purpose small business, debt consolidation, renewal energy, educational, house and other is showing high chances of default.



## Technologies and Libraries Used
- Python 3.9.12 (main, Apr  4 2022, 05:22:27) [MSC v.1916 64 bit (AMD64)]
- Jupyter notebook server - version 6.4.8
- IPython 8.2.0
- pandas - version 1.5.1
- numpy - version 1.23
- matplotlib - version 3.6.2
- seaborn - version 0.12.1



## Steps Covered
- Data Cleaning
- Sanity Checks
- Univariate/Segmented Univariate Analysis
- Bivariate/Multivariate Analysis
- Observations, Recommendations & Insights


## Contributors
- Facilitator: Siddharth Singh
- Group Member: Vernica Ahuja