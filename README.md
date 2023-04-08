# Food Delivery App Data Analysis
Project description from HiCounselor's Linkedin URL: https://www.linkedin.com/posts/hicounselor_ugcPost-7043499029141274624-YIZl?utm_source=share&utm_medium=member_desktop

### Project Description: 
This project will help you understand how a real-world database is analyzed using SQL, how to get maximum available insights from the dataset, pre-process the data using python for better upcoming performance, and how a structured query language helps us retrieve useful information from the database.

### Module 1: Data Preprocessing 
In this module, you will query the dataset using structured query language to gain insights from the database. The problem statements to be solved will be provided to you, and you will need to provide the solution for the same using your logic. Different concepts of SQL will be used in this process, such as aggregating the data, grouping the data, ordering the data, etc

#### Task 1: Pre-Processing The Data And Removing Unwanted Columns
In this module, you will query the dataset using structured query language to gain insights from the database. The problem statements to be solved will be provided to you and you need to provide the solution for the same using your logic. Different concepts of SQL will be used in this process such as aggregating the data, grouping the data, ordering the data, etc. Module 1 consists of subtasks which are as follows

#### Pre-processing the data: 
Data Pre-processing is one of the important steps in data analytics because data that is not processed can lead to different unwanted results when the data will be used for further applications. This task includes sub-tasks such as handling null values, deletion or transformation of irrelevant values, datatype transformation, removing duplicates, etc. The tasks to be performed for cleaning the data set are given below:

#### Removing Unwanted Columns: 
Removing unwanted columns refers to the process of eliminating irrelevant or unnecessary columns from a dataset. This can improve data analysis and visualization by reducing clutter and focusing on the most important information. It involves identifying and selecting the columns to be removed and executing the removal process using tools like programming languages, database management systems, or spreadsheet software.

#### Task 2: Renaming And Selecting Columns In A Dataset
Renaming columns involves changing the names of one or more columns in a dataset to make them more meaningful or consistent. Selecting columns refers to the process of choosing only specific columns to be included in a dataset while excluding all others. These techniques are useful for improving the organization and readability of data and can help streamline data analysis. By renaming and selecting only the relevant columns, data scientists can create a more focused and manageable dataset that is better suited for their specific analysis needs.
Only these columns are allowed in the dataset:
Id 2. Name 3. online_order 4. book_table 5. rating 6. votes 7. location 8. rest_type 9. dish_liked 10. cuisines 11. approx_cost 12. type

#### Task 3: Dealing With Null Values In A Dataset
Handling null values refers to the process of identifying and addressing missing or incomplete data in each column of a dataset. This involves using techniques like imputation, where missing values are replaced with estimated values based on other data, or deletion, where incomplete records are removed entirely. Proper handling of null values is critical for accurate data analysis and can help prevent bias and errors in results.

#### Task 4: Identifying Duplicate Data In A Dataset
Finding duplicates in a dataset refers to the process of identifying records that are identical or nearly identical to one another. Duplicate data can skew analysis results and waste computational resources, so it is important to identify and remove duplicates before analyzing data. This can be achieved using algorithms that compare records and identify common attributes, or through manual inspection of the dataset.

#### Task 5: Text Cleaning
Text cleaning refers to the process of removing irrelevant or unnecessary text from all the columns in a dataset. This is an essential step in data preprocessing and analysis, as it ensures that the data is accurate and reliable. Text cleaning can involve tasks such as removing stopwords, punctuation, and special characters, as well as correcting spelling and grammar errors.

#### Task 6: Unique Value Check And Irrelevant Value Handling
The process of examining each column in a dataset to identify and handle any irrelevant data, while also verifying the uniqueness of values within each column. This helps ensure data accuracy and integrity in analysis and decision-making.

#### Task 7: Cleaning And Exporting Zomato Dataset
The process of cleaning the Zomato dataset by removing any unknown or unidentifiable characters and exporting the cleaned dataset to a new file named "zomatocleaned.csv". This involves identifying and removing any symbols, special characters, or non-standard characters that may interfere with proper data analysis. By exporting the cleaned dataset to a new file, the original dataset can be preserved and the cleaned data can be easily accessed for further analysis and decision-making.

#### Task 8: Data Cleaning And Analysis With Excel And MySQL
The process of performing data cleaning and analysis using both Excel and MySQL. The first step involves the deduplication of identical rows in an exported dataset using Excel. This helps ensure data accuracy and consistency. The second step involves uploading the cleaned dataset to a provided database and performing further analysis using MySQL. This allows for powerful data querying and visualization, enabling data-driven decision-making.

Step 1: Download the exported data set "zomatocleaned.csv".

Step 2: Eliminate any identical rows in the Excel dataset by performing the deduplication task. 

Step 3: Upload the final dataset to the database provided to conduct an analysis in MySQL. 

Step 4: Retrieve the database host, username, password, and database information from the "Database Info" tab and input it into db.py. 

Step 5: To complete the current task, click on "Run Test" and confirm that your table has been successfully created.

### Module 2: Data Analysis Using SQL
In this module, you will be working on performing data analysis on the pre-processed data from the previous module and conducting Data Analysis using SQL. You will generate queries for given problem statements. 

#### Task 1: Write An SQL Query To Solve The Given Problem Statement: 
For a high-level overview of the hotels, provide us the top 5 most voted hotels in the delivery category.

#### Task 2: Write An SQL Query To Solve The Given Problem Statement: 
The rating of a hotel is a key identifier in determining a restaurant’s performance. Hence for a particular location called Banashankari find out the top 5 highly rated hotels in the delivery category.

#### Task 3: Write An SQL Query To Solve The Given Problem Statement: 
Compare the ratings of the cheapest and most expensive hotels in Indiranagar.

#### Task 4: Write An SQL Query To Solve The Given Problem Statement: 
Online ordering of food has exponentially increased over time. Compare the total votes of restaurants that provide online ordering services and those that don’t provide online ordering services.

#### Task 5: Write An SQL Query To Solve The Given Problem Statement: 
Number of votes defines how much the customers are involved with the service provided by the restaurants For each Restaurant type, find out the number of restaurants, total votes, and average rating. Display the data with the highest votes on the top( if the first row of output is NA display the remaining rows).

#### Task 6: Write An SQL Query To Solve The Given Problem Statement: 
What is the most liked dish of the most-voted restaurant on Zomato(as the restaurant has a tie-up with Zomato, the restaurant compulsorily provides online ordering and delivery facilities.

#### Task 7: Write An SQL Query To Solve The Given Problem Statement: 
To increase the maximum profit, Zomato is in need to expand its business. For doing so Zomato wants the list of the top 15 restaurants which have min 150 votes, have a rating greater than 3, and is currently not providing online ordering. Display the restaurants with the highest votes on the top.
