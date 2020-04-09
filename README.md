# Seek.com.au-extract
Pulling job ads from Seek.com.au to analyze keywords and salaries.

The goal of this project is to extract and explore the job ads on Seek website.

The final objective is to understand the keywords used in job titles vs job description, compare salaries where available and observe
posted job ads frequency on the website over time.

HOW:
Data will be pulled from Seek.com.au
Script is written in Python.
Scrip will run on EC2's and data is stored on Redshift.
Each job ad containts the following and the script will capture all following values:
- Title
- Company Name
- job Description
- Date Advertised
- Location
- Salary
- Work Type
- Job Category
