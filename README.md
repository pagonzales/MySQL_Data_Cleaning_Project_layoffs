# MySQL_Exploratory_Data_Analysis_Project 
## Project Objective
To clean a raw data file using MySQL and make the data ready for further exploratory data analysis of companies that laid off employees in the year March 2020 to March 2023.
## Data used
- <a href = "https://github.com/pagonzales/MySQL_Data_Cleaning_Project_layoffs/blob/main/layoffs%20raw%20data.csv">Data used</a>
## Questions
- What industry has the top total laid off employees.
- What are the top 5 countries with maximum laid off employees.
- List the sum of the total laid off employees in terms of year.
- What are the top companies that has a maximum laid off employee in each year.
## Procedure
- Create first a staging to have the raw data secured from all the possible irreversible errors.
- Remove all the duplicates for the data to be clean.
- Standardize the data (like removing unnecessary spaces in between company names or making some industry names in standard text, etc., making the format of date more readable, etc.).
- Remove null or blank values,
- And finally, remove irrelevant rows or columns.
- For Exploratory Data Analysis, use commands such as (but not limited to) CTEs, Substrings, Rolling total, and Dense rank to analyze the data.

## Project Insights
- The findings covering the period from March 2020 to March 2023 are listed below:
  - The industry with maximum total laid off employees come from consumer, followed by retail.
  - The Top 5 countries with maximum laid off employees are
    - United States with 256559 laid off employees.
    - India with 35993 laid off employees.
    - Netherlands with 17220 laid off employees.
    - Sweden with 11264 laid off employees.
    - Brazil with 10391 laid off employees.
  - The sum of total laid off employees in years are as follows:
    - In 2023, there are total of 125677 laid off employees.
    - In 2022, there are total of 160661 laid off employees.
    - In 2021, there are total of 15823 laid off employees.
    - In 2020, there are total of 80998 laid off employees.
  - The Top companies with maximum laid off employees are listed below:
    - In 2020, Uber has laid off a total of 7525 employees.
    - In 2021, Bytedance has laid off a total of 3600 employees.
    - In 2022, Meta has laid off a total of 11000 employees.
    - In 2023, Google has laid off a total of 12000 employees.

## Final Conclusion
In the period of March 2020 to March 2023, 2022 may seem to be the year with the most laid off employees but as we can see from 2023, it gathered almost 78% laid off employees compared to 2022 in just 3 months.
Also, this increasing number maybe due to the covid pandemic as the year coverage in the raw data provided was exactly in the covid pandemic. It might show the aftermath effect of the pandemic to the companies and employees.





