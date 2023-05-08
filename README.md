# Parental Leave Project

This is a data analytics project that involves working with a dataset obtained from [the Maven Family Leave Challenge](https://www.mavenanalytics.io/challenges/maven-family-leave-challenge/2). 
The dataset consists of a CSV table containing 1,601 records, with each record representing a different company. 
The data includes information on the company's name, industry, and crowdsourced data on the paid and unpaid weeks off they offer as part of their maternity and paternity leave policies (when available).

After uploading the dataset to a Microsoft SQL Server database, some data cleaning was performed using SQL to ensure the accuracy and relevance of the data.

The main analysis questions for this project include:

- Which industries offer the highest number of paid and unpaid parental leave weeks?
- What is the average number of parental leave weeks offered by companies?
- What percentage of companies offer parental leave?
- How many companies offer 1 to 5, 6 to 10, 11 to 15, and so on weeks of parental leave?

The insights obtained from the analysis will be communicated through clear and impactful visualizations created using Power BI.

## Data Import & SQL Data Cleaning

The [raw dataset](./data/parental_leave_raw.csv) from Maven was saved as an Excel Worksheet and loaded into Microsoft SQL Server using the 64-bit import wizard, and SQL was used to perform data cleaning to ensure the accuracy and relevance of the data in order to answer the key analysis questions.

The SQL data cleaning included:

- Splitting Industry and SubIndustry into two columns. ([See the SQL queries used for this task](SQLqueries/SplittingIndustrySubIndustry.sql))

