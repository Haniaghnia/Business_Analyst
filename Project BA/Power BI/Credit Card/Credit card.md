## [Data Engineering]()
 See on Power BI: [Insights](https://github.com/Haniaghnia/Hani_Portfolio/blob/dafa719edb6d061a70fde0c5815a0fbd0a1460c5/Power%20BI/DE/DE%20BTPN.pbix)  

### Project Background
* Analyzing Bank BTPN credit card customer database, see the risks that will arise, and how preventive actions can be taken. 
* Using a methodology with seven steps to solve the problem Identify the business objectives, Define the problem statement and goals of the analysis,  Exploratory Data Analysis (EDA), Analyze the data, Draw a conclusion and develop a portfolio management plan.
* With the data that is owned, it performs data processing based on business objectives, data exploration and generates insights for the company.

#### 1. Introduction 
Bank BTPN Indonesia is a universal bank that provides various products and services to corporate and individual customers. One of the products offered by Bank BTPN, one of Indonesia's banking institutions, is a credit card. A large portion of revenue growth comes from credit cards. Despite revenue growth, many consumers are experiencing
defaults. To increase revenue, it is necessary to understand the risks that will arise and how preventive actions can be taken.

#### 2. Goal
Often, companies have data that contain a lot of hidden information. Using data analysis increases efficiency and  improves performance by discovering patterns in data. The goal is to answer the right questions that will help the company to make the right decisions.  Identify the key drivers of credit risk and develop a portfolio management strategy for a financial institution.

#### 3. Methodology
Methodology refers to the systematic and structured approach used to conduct research or analysis. In this project, we solve the problem using seven steps.
1. Identify the business objectives 
2. Define the problem statement and goals of the analysis
3. Exploratory Data Analysis (EDA) 
4. Analyze the data 
5. Draw Conclusion
6. Develop a portfolio management

##### Step 1 : Identify the business objectives 
It is important to determine the main goals of the project and the people or groups of people who will be affected by the results of the analysis. Define the problem statement and goals of the analysis, using the 5 Whys technique to get to the root of the problem. 

##### Step 2 : Define the problem statement and goals of the analysis
Define the problem statement: Start by clearly defining the problem statement, which in this case is identifying potential risks in the credit customer database.
Define the problem statement and goals of the analysis, using the 5 Whys technique to get to the root of the problem.
1.	Identify the problem: The financial institution is experiencing high credit risk in its portfolio.
2.	Why is the credit risk high?
The credit risk is high because the institution is lending to borrowers who are not creditworthy.
3.	Why is the institution lending to non-creditworthy borrowers?
Bank BTPN is lending to non-creditworthy borrowers because it does not have a robust credit risk management process in place.
4.	Why does the institution not have a robust credit risk management process in place?
Bank BTPN  does not have a robust credit risk management process in place because it lacks the necessary information systems and analytical techniques to measure credit risk.
5.	Why does the institution lack the necessary information systems and analytical techniques to measure credit risk?
Bank BTPN  lacks the necessary information systems and analytical techniques to measure credit risk because it has not invested in developing these systems and techniques.

##### Step 3 : Exploratory Data Analysis (EDA) 
###### Step 3.1 :  Collect data
Collect data from various sources, such as loan application forms, credit bureau reports, and financial statements, and prepare the data for analysis using SQL and other relevant software.
The data is publicly from Bank BTPN and stored in 5 CSV files, Data collected includes (1) Customer data history, (2) Card category, (3) Education, (4) Martial status, and (5) Status customer. With a total of all customers of 10.128. To start processing data, use PostgreSQL as one of the data analytics tools, to import datasets, and carry out cleaning and organizing processes. The cleaning process includes adjusting data type formats and removing duplicate data and nulls. I extracted the clean data to a new CSV and saved it. I document the entire cleaning process.

###### Step 3.2 : Conduct Exploratory Data Analysis (EDA) 
Cleaning, transforming, and manipulating the dataset will be used to do the analysis process. Using my analytical skills.

##### Step 4 : Analyze the data
![](https://github.com/Haniaghnia/Business_Analyst/blob/3c8a002df6860f00be3f3a2ede68bc1cf75eba16/Project%20BA/Power%20BI/Credit%20Card/BTPN.PNG)

##### Step 5 : Draw Conclusion
1.	One of the factors that determine whether a customer will continue to make a loan or not is monthly income and age.
2.	With the results of the company's insight, it can carry out auto screening, with conditions when customers who register have an income of less than $40, and at 44-57 years old then, we can enter into a strong potential customer profile failed to pay.

##### Step 6 : Develop a portfolio management
The final step is to develop a portfolio management strategy that takes into account the risk appetite of the financial institution and the characteristics of the borrower. Based on the insights gained from the analysis, The process involves developing a risk model, setting risk thresholds, and identifying strategies to manage risk in the portfolio, which is not included in this project due to data limitations.
