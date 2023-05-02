## [Credit Risk Analysis]()
 See on Power BI: [Insights](https://github.com/Haniaghnia/Hani_Portfolio/blob/dafa719edb6d061a70fde0c5815a0fbd0a1460c5/Power%20BI/DE/DE%20BTPN.pbix)  

### Credit Risk Analysis and Portfolio Management
*	Identify the business objectives and key stakeholders for the project.
*	Define the problem statement and goals of the analysis, using the 5 Whys technique to get to the root of the problem.
*	Collect data from various sources, such as loan application forms, credit bureau reports, and financial statements, and prepare the data for analysis using SQL and other relevant software.
*	Conduct exploratory data analysis (EDA) using Python identify patterns and trends in the data.
*	Analyze the data to identify key drivers of credit risk, such as income level, credit score, and loan-to-value ratio.
*	Develop a portfolio management strategy that takes into account the risk appetite of the financial institution and the characteristics of the borrower population.
*	Present findings and recommendations to key stakeholders, using clear and concise language and relevant visual aids such as charts and graphs.


#### Step 1 : Identify the business objectives and key stakeholders for the project
It is important to determine the main goals of the project and the people or groups of people who will be affected by the results of the analysis. Define the problem statement and goals of the analysis, using the 5 Whys technique to get to the root of the problem. 


#### Step 2 : Define the problem statement and goals of the analysis, using the 5 Whys technique to get to the root of the problem.
Start by clearly defining the problem statement, which in this case is identifying potential risks in the credit customer database.

##### 1. Identify the problem: The financial institution is experiencing high credit risk in its portfolio.
##### 2. Why is the credit risk high?
The credit risk is high because the institution is lending to borrowers who are not creditworthy.
##### 3. Why is the institution lending to non-creditworthy borrowers?
Bank BTPN is lending to non-creditworthy borrowers because it does not have a robust credit risk management process in place.
##### 4. Why does the institution not have a robust credit risk management process in place?
Bank BTPN  does not have a robust credit risk management process in place because it lacks the necessary information systems and analytical techniques to measure credit risk.
##### 5. Why does the institution lack the necessary information systems and analytical techniques to measure credit risk?
Bank BTPN  lacks the necessary information systems and analytical techniques to measure credit risk because it has not invested in developing these systems and techniques.

#### Step 3 : Collect data from various sources, such as loan application forms, credit bureau reports, and financial statements, and prepare the data for analysis using SQL and other relevant software.
The data is publicly from Bank BTPN and stored in 5 CSV files, Data collected includes (1) Customer data history, (2) Card category, (3) Education, (4) Martial status, and (5) Status customer. With a total of all customers of 10.128. To start processing data, use PostgreSQL as one of the data analytics tools, to import datasets, and carry out cleaning and organizing processes. The cleaning process includes adjusting data type formats and removing duplicate data and nulls. I extracted the clean data to a new CSV and saved it. I document the entire cleaning process.

#### Step 4 : Conduct exploratory data analysis (EDA) using Python identify patterns and trends in the data.
Cleaning, transforming, and manipulating the dataset will be used to do the analysis process. Using my analytical skills.

#### Step 5 : Analyze the data to identify key drivers of credit risk, such as income level, credit score, and loan-to-value ratio.
 I analyzed the data to identify trends and patterns that could help answer the business task and objectives. I also used my knowledge of the banking industry to draw relevant insights that would benefit the organization.
 
#### Step 6 : Develop a portfolio management strategy that takes into account the risk appetite of the financial institution and the characteristics of the borrower population.
Drew conclusions and made recommendations based on the data, then I used communication skills to present the findings in a clear and concise manner to the stakeholders.

#### Step 7 : Present findings and recommendations to key stakeholders, using clear and concise language and relevant visual aids such as charts and graphs.
Ensured that I used simple and easy-to-understand language to convey complex data findings. Additionally, Used relevant visuals such as charts and graphs to make the data more accessible to stakeholders.
![](https://github.com/Haniaghnia/Hani_Portfolio/blob/dafa719edb6d061a70fde0c5815a0fbd0a1460c5/Power%20BI/DE/DE.PNG)
1.	One of the factors that determine whether a customer will continue to make a loan or not is monthly income and age.
2.	With the results of the company's insight, it can carry out auto screening, with conditions when customers who register have an income of less than $40, and at 44-57 years old then, we can enter into a strong potential customer profile failed to pay.
