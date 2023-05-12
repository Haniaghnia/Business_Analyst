# [Project Coffee Shop with Agile Methodology]()
 See on Tableau Public: [Dashboard](https://public.tableau.com/shared/2ZN5FRJJ7?:display_count=n&:origin=viz_share_link)  

![](https://github.com/Haniaghnia/Business_Analyst/blob/1e4af1365bbdef87262cd52d68bb934cf4fd0e60/Project%20BA/Coffee%20Shop/Coffee.png)
## Introduction 
Food and Beverage company currently focusing on developing the Coffee Shop business. The company wants to develop its product and see how insight is related to sales at the current Coffee Shop. Define business and data needs could be to analyze customer behavior data for a retail company. The goal of this project would be to provide insights to help the company better understand its customers and improve its business strategy and create a business solution report satisfying all the demands of the client (as per the specified acceptance criteria) mentioned in the business request document.

### Business Case 
As business intelligence begins to start the project, understanding the client's demands The owner of the coffee shop had sent a business request in the form of an email stating their requirements and demands.

![](https://github.com/Haniaghnia/Business_Analyst/blob/1e4af1365bbdef87262cd52d68bb934cf4fd0e60/Project%20BA/Coffee%20Shop/BC.PNG)


### Project Background
To achieve this goal, follow an agile methodology, specifically the SCRUM framework. The first step will be to gather the requirements and define the scope of the project. This will involve meeting with stakeholders, including the coffee shop owner, the marketing team, and the sales team, to understand their needs and expectations. From this meeting, create a list of user stories that will guide the project.

The next step is to start the project by creating a backlog of tasks to be completed. This will include data gathering, cleaning, and processing, as well as developing SQL queries to explore the data.

After analyzing the data, I will develop a plan to improve the new product based on customer habits and profiles. This will involve developing marketing and sales strategies that target specific customer segments based on gender, loyalty, and age range. I will create acceptance criteria to ensure that the strategies are effective and aligned with the stakeholders' expectations.

Once the plan is developed, I will execute the project by working with the marketing and sales teams to implement the strategies. I will monitor the progress of the project and make adjustments as needed to ensure that the goals are being met. Finally, I will present the results to the stakeholders and evaluate the success of the project based on the value proposition of increased revenue and a new product marketing strategy.


#### To start the project, the first step is
##### 1.	Define the Problem and Business Objective:
To identify the problem and the overall objective of the project and determine the exact demands of the customer, starting with a one-on-one meeting with the designated person helps us map the client's mind and get on our journey. The owner wants to increase revenue by increasing purchases of new products and understand its customers and improve its business strategy.

###### 1.1 List Backlog project 
The backlog of tasks for the project:
1. Conduct an initial meeting with the coffee shop owner to gather requirements and understand project goals.
2. Identify the stakeholders 
3. Create the BRD, which outlines the business needs and objectives.
4. Collect data on sales performance, customer behavior, and product information from coffee shops.
5. Use SQL queries to process and analyze the data.
6. Create initial Tableau visualizations to explore the data and identify trends, and a dashboard overview of sales performance.
7. Tableau visualizations for tracking new product dashboard performance
8. Create a product drill-down visualization to identify top-performing products, categories, and outlets.
9. Analyze customer habits and profiles to determine an improvement strategy for sales.
11. Implement features using agile methodology and the Scrum framework.
12. Conduct daily stand-up meetings to track progress and identify issues.
13. Conduct sprint review meetings to review completed work and identify improvements.
14. Conduct sprint retrospective meetings to reflect on the previous sprint and identify areas for improvement.
15. Repeat steps 10–14 for subsequent sprints until project goals are achieved.
These tasks can be further broken down into smaller tasks and assigned to specific team members with appropriate deadlines.


##### 2.	Gather Requirements:
Documentation is a critical part of project development. Ensuring projects are successful and meet the needs and expectations of stakeholders is also the foundation of all further project deliverables, describing what inputs and outputs are associated with each process function. The Business Requirements Document (BRD) is an essential step in the business analyst process for the project of analyzing a coffee shop's business development. The BRD contains a SWOT analysis of the project and how it fits into the big picture. Using BRD to outline the business needs and objectives for analyzing the coffee shop's business development for new products The project will focus on identifying which products have good sales performance, which product categories are sold the most, and which outlets have the best sales. Furthermore, this project will determine customer habits and profiles to develop an improvement strategy for sales.

**IMPROVING NEW PRODUCT COFFEE SHOP AGILE BUSINESS REQUIREMENTS DOCUMENT**
The components of the Business Requirements Document (BRD) using Agile methodology are listed below.

![](https://github.com/Haniaghnia/Business_Analyst/blob/3191ded675d6fd2a2348b58a9e37103620b6fed2/Project%20BA/Coffee%20Shop/Table%20BRD.PNG)

[BRD](https://github.com/Haniaghnia/Business_Analyst/blob/24e1fa11de83d39aac8d61ffef49568fecded3dd/Project%20BA/Coffee%20Shop/BRD%20Coffee%20Shop.pdf)  


##### 3. Data Exploration
###### 3.1 Collect the data
The client has provided the backup sales database combination of fact as well as dimension table data. The data from the Coffee Shop business is in 5 CSV files, Data collected includes (1) Customer data, (2) Outlet data, (3) Product Data, (4) Staff Data, and (5) Transaction data. With a total all customers 2246 and total transactions of 49.894

###### 3.2 SQL queries for data analysis
To start processing data, use PostgreSQL as one of the data analytics tools, to import datasets, and carry out cleaning and organizing processes. The cleaning process includes adjusting data type formats and removing duplicate data and nulls. I extracted the clean data to a new CSV and saved it. I document the entire cleaning process.
Show SQL data manipulation 
[SQL data manipulation](https://github.com/Haniaghnia/Business_Analyst/blob/3191ded675d6fd2a2348b58a9e37103620b6fed2/Project%20BA/Coffee%20Shop/Data%20Manipulation.sql)
Data modeling is used to organize and structure data in a way that is easy to understand. Involves identifying the data that needs to be captured, organizing the data into logical groups, and defining the relationships between the data. It is used to analyze the data requirements that are required for business processes.
Start modeling using SQL to create the schema diagram. The primary keys of the dimension table are connected to the corresponding foreign key of the fact sales table on a one-to-many basis, as shown below.


##### 4.	Data Visualization
###### SQL Tableau Visualization 
###### 4.1	Sales Overview:
How are coffee shop sales in April 2019? The Sales Overview Dashboard is an interactive real-time sales analysis dashboard that fulfills the first business request for migration from static reports to interactive reports.

The sales overview also shows
-	total sales for all coffee shop outlets by city and type of product, allowing for proper visualization of the profits made.
-	Top 10 Products Based on Sales and Customers, which were also part of the Business Demand Overview
-	Sales day by day with average sales in one month period to see target achievement every day
![](https://github.com/Haniaghnia/Business_Analyst/blob/034d7d014a536fe4de4a630328b31ec6f588863e/Project%20BA/Coffee%20Shop/Sales%20Overview.PNG)

###### 4.2	New Product :
Product Details : 
-	The dashboard displays more specific sales data by week.
-	Sales by Product Category
-	Sales of the top 10 new products over time
![](https://github.com/Haniaghnia/Business_Analyst/blob/034d7d014a536fe4de4a630328b31ec6f588863e/Project%20BA/Coffee%20Shop/New%20Product.PNG)

###### 4.3 Customers Details : 
-	Specific transaction detail by hours based on age
-	Transaction of New Products by Age and Gender
-	Customer composites and purchases new product compositions
![](https://github.com/Haniaghnia/Business_Analyst/blob/034d7d014a536fe4de4a630328b31ec6f588863e/Project%20BA/Coffee%20Shop/Customers.PNG)


##### 5.	Data Analysis
Customer behavior analysis and Improvement strategy report
- Customer behavior analysis report
-	Customers aged between 25 and 35 years are more likely to try new products. 
-	The largest percentage of customers who try new products is 1-year customer loyalty. 
-	Men, although the number is lower than women's, have a larger proportion of new product buyers.


##### 6.	Recommendation
###### 6.1	 Improvement strategy report
-	In increasing product sales, especially the newest product, the right time is at the end of the month, on the last dates at the office, which is the busiest time, but purchases increase due to payday. Offers at 8 am, 14 pm, or 5 pm. And for new customers and customers < 1 year.
-	There is a product that is not feasible, namely Loose tea because it has the smallest sales. To get maximum results to focus on Tea and Coffee. If there are cost constraints, discontinuing Loose Tea products can save storage costs and capital costs

###### 6.2	Implement features using agile methodology and the Scrum framework.
Implement features using agile methodology and the Scrum framework.
o	Conduct daily stand-up meetings to discuss progress, identify obstacles, and plan for the day ahead. Meetings should be brief and focused, with each team member answering three questions: What did you do yesterday? What are you planning to do today? Do you have any obstacles?
o	Conduct sprint reviews at the end of each sprint; also discuss what went well during the sprint and what could be improved in the next sprint.
o	Conduct a sprint retrospective meeting to reflect on the sprint and identify areas for improvement. The team should discuss what worked well, what didn't work well, and what can be improved in the next sprint.

Conduct daily stand-up meetings to track progress and identify issues.


##### 7.	Monitor and Evaluate
Continuously monitor and evaluate the performance of the company after the implementation of the solutions to ensure that the desired outcome is achieved.


