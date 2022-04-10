# LENDING CLUB CASE STUDY
Strategy: Borrowers can easily access lower interest rate loans through a fast-online interface.
Business Objective:
▪ Lending loans to ‘risky’ applicants is the largest source of financial loss or credit loss
▪ To identify the borrowers who default and cause the largest amount of loss to the lenders
Goals of Data Analysis:
❑Identify the risky loan applications: Identify risky loan applicants using EDA (Exploratory Data Analysis), then
such loans can be reduced thereby cutting down the amount of credit loss to the company.
❑Identify driving factors behind loan default: Analyze the driving factors (driver variables) behind loan default, i.e. the variables which are strong indicators of default like ‘Annual Income’, ‘Term’ of loan, ‘Interest Rate’ etc. The company can utilize this knowledge for its portfolio and risk assessment.
❑ Risk Analytics: Understanding the types of variables and their significance to check the distribution of default rate across various driving variables.


## Table of Contents
* Objectives
* Problem solving methodology: General Approach
* Analysis (Univariate Analysis, Bi-variate Analysis along with visual Representation)
* Conclusions and Recommendations


## General Information
Identified and removed redundant and unnecessary columns from the ‘loan’ data set
• Performed data cleaning on ‘loan’ data sets to remove the junk data (Columns having 100% null values and rows
where the entire row is having null values) and the data which is not required for analysis
• Analyzed the variables and their different data types, also performed null value checks for the variables.
Data Cleaning and Manipulation
• Data quality issues are addressed in the right way (missing value imputation, outlier treatment and other kinds of data redundancies
• Wherever applicable, data is converted to a suitable and convenient format to work with using the right methods for e.g. converting date type columns to date type format and converting numeric column to int or float
• Extracted numeric values from the columns like ‘Interest rate’
• Manipulation of strings and dates is done correctly wherever required

## Conclusions
Based on the univariate analysis of driving factors for the ‘Default Rate’ the top important variables are as below:
• Term : As the Loan term increases default rate also increases. Loan Term 60 months has more ‘Rate of Default’
• Loan Amount : There is a significant increase in the ‘Default Rate’ as the loan amount increases
• Annual Income : There is a direct correlation between the annual income and ‘Rate of Default. As the Annual income decrease, rate of default increases. Applicants having low annual income have more rate of default.
• Grade : There is a significant increase in the ‘Default Rate’ as we go from Grade A towards Grade G.
• Sub-Grade : Subgrade follows the same trend as Grad for ‘Default Rate’
• Interest Rate : There is a direct correlation between the interest rate and ‘Rate of Default. As the interest rate increases, rate of default also increases.
• VerificationStatus:‘VerifiedStatus’havemore‘DefaultRate’

Based on the Bi-variate analysis of driving factors for the ‘Default Rate’, below are the conclusions: • ‘Purpose of Loan’ for each ‘Term’ against ‘Default Rate’ : The distribution represents that as the term increases
the ‘Default Rate’ also increases for each type of ‘Purpose of Loan’. Term 60 months, has higher ‘Rate of Default’
• Employment length in years against the ‘Loan Amount : A scatter plot distribution of ‘Emp Length’ against the ‘Loan Amount’ represents that there is a decrease in the Loam Amount as the employment length or the experience of an employee increases from 0 to 10 years. (10 years being an outlier in the given distribution)

## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- seaborn - version 0.11.2


## Acknowledgements
-Refered required information from https//www.google.com

## Contact
Created by Yogesh Kolhe & Fahad Baigh. 
[https://github.com/yoyoyogesh/LendingClubCaseStudy] - feel free to contact us!
