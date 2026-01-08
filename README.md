# SQL-oldest-business-in-the-world-

OLDEST BUSINESS IN THE WORLD Project description
An important part of business is planning for the future and ensuring that the business survives changing market conditions. Some businesses do this remarkably well and last for hundreds of years. In this project, you'll explore data from BusinessFinancing.co.uk on the world's oldest businesses: when were they founded, and which industries do they belong to?
 Public
Public
Image: St. Peter Stiftskeller, founded 803. Credit: Pakeha.
DATA PREPARETION
First step to perform is to upload the dataset to a SQL database. In this case I am using “PostgreSQL” to run this project.
This step is not necessary if you already have your data in a SQL server. In this case I wanted to do the project from scratch and follow all the steps from database creation, to creating the table to loading the data and finally querying the data to answer the questions.
• Create database
• Create table
• Import csv file
   

Public
 QUESTIONS TO ANSWERED
What are the oldest and newest founding years
• Oldest founding year
   

• Newest founding year
How many businesses were founded before 1000?
Public
     Which businesses were founded before 1000?



  Exploring the categories: Select the business name, founding year, and country
 code from businesses, and category from categories
  Counting the categories: what other industries constitute the oldest companies
 around the world, and which industries are most common.



  Oldest business by continent: where in the world these really old
 businesses are?
  Joining everything for further analysis: join the three tables (business, categories
 , countries)



 • Counting categories by continent: which are the most common categories for the oldest businesses on each continent?
In [0]:
 •
Filtering counts by continent and category: what are the categories with higher number than 5
Public


 
