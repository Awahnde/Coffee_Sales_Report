# Expresso Escape: Coffee Sales Dashboard

<img width="1700" height="622" alt="image" src="https://github.com/user-attachments/assets/940608f6-4901-478f-a816-13f273c8d96d" />




## The Situation
Recently became a franchise owner at a fictious coffee shop chain called 'Expresso Escape' managing three high-traffic locations across New York City. Through hands-on data analysis using Excel dashboards, I transformed raw sales patterns into actionable insights—spotting peak hours and optimizing staffing to boost revenue while building authentic customer connections in the city's fast-paced rhythm.

## The Assignment
To understand purchase behaviour and streamline operations transactional data from Jan – Jun 2023 was collected, prepared and analyzed.

The objective is to transform the data into a dynamic dashboard that franchise owners can use to identify patterns, trends and opportunities for the business.

1.	Profile and prepare the raw data for analysis.
2.	Explore the data with Excel PivotTables.
3.	Build a dynamic dashboard to visualize patterns and trends.


## Data

Coffee Shop Sales: Transaction records from a fictitious coffee shop in New York City
Dataset  
File type: Excel
Data structure: Single table
of records: 149116
of fields: 11

## Data Preparation

Prepare the Data for Analysis:
1.	Familiarized myself with the data. Determined how many transactions recorded, over the period of time and the types of products and product categories sold.
2.	Added a ‘revenue’ column where price * quantity
   
     #### Revenue = [@[unit_price]]*[@[transaction_qty]]

3.	I added new columns to calculate the Month as ‘Feb’ and Day of Week as ‘Tuesday’

    3.1	To extract the day from the date I used the following formula

  	#### =TEXT([@[transaction_date]];"dddd")
  	
    3.2	To extract the month from the date I used the following formula

    #### =TEXT([@[transaction_date]];"mmm")

5.	Added a new column to extract the ‘hour’ from the transaction time

6. To extract the hour I used the hour() function.

## Data Analysis

Explore the Data with pivot tables:

1.	Inserted a pivot table on a new tab to show revenue by month.

   <img width="555" height="273" alt="image" src="https://github.com/user-attachments/assets/c39dab62-1811-4a95-9c9c-e7314727b123" />


3.	Added to more pivot tables to show the number of transactions by day of week and by hour of day.

   <img width="392" height="539" alt="image" src="https://github.com/user-attachments/assets/33425054-5657-4c20-abd4-b99188550adf" /> 

   <img width="372" height="288" alt="image" src="https://github.com/user-attachments/assets/774fba2c-b8ca-4618-a217-ce090850bd83" />

                
5.	Added a pivot table to show the number of transactions by product category and sorted in descending by transactions.

   <img width="478" height="402" alt="image" src="https://github.com/user-attachments/assets/d4db0b37-fc67-47ad-8107-ce5ccc2ed1fd" />


7.	And finally added another pivot table to show the number of transactions and revenue by product type. Sorted the table in descending order and filtered it to the top 15 by transactions.

   <img width="711" height="534" alt="image" src="https://github.com/user-attachments/assets/09450c16-3b6b-48ad-9e1d-df132aa102eb" />

    
## Results
Coffee Sales Dashboard 
<img width="1700" height="622" alt="image" src="https://github.com/user-attachments/assets/5747d102-7191-4016-9f3a-227ffc0bfea6" />

## Recommendations

