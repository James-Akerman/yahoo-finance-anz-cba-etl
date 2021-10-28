## Instructions:
- Run jupyter Notebook environment

- Set up MongoDB connection

- Pip install packages required in Complete ETL Process.Ipynb

- Run the ***Complete ETL Process.Ipynb*** jupyter notebook.

***Caution:*** 
For where requires directory path, please change {user} according to your own file path as the example below:

user = '{UserName}'

file_directory = 'Desktop\\etl-project'

- prefs = {"download.default_directory" : f"/Users/{user}/Desktop/Bootcamp/etl-project"}

##### Note: The ***Complete ETL Process.Ipynb*** jupyter notebook includes entire ETL process in one integrated script.


## Alternatively - Go to the ***'seperate_collection_etl_processes'*** directory and run each of the following scripts to run the complete etl process
- yahoo finance_ANZ CBA_Balance_sheets.ipynb
- yahoo finance_ANZ CBA_Stock History Year Month Average
- yahoo finance_ANZ CBA_Stocks Cash Flow.ipynb
- yahoo finance_ANZ CBA_Stocks Income statements.ipynb
- yahoo finance_ANZ CBA_Stocks Summary Table.ipynb

## Outcomes of running this ETL include: 
- Creating database and collections in MongoDB
- Saving Historical Data as CSV file into local directory

## A Report describing the aims, purpose, and further information about this ETL process is included called ***'ETL Report_Group 7.pdf'***

## Resouces used for this project
- Data Resources: Yahoo Finance
  1) ANZ: https://au.finance.yahoo.com/quote/ANZ.AX
  2) CBA: https://au.finance.yahoo.com/quote/CBA.AX
- Web Scraping Tools: Beautiful Soup, Selenium
- Database: MongoDB
