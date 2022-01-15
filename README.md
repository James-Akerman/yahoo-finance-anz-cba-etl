# Yahoo Finance ANZ/CBA ETL
This is an ETL (extract, transform, load) process which scrapes several pages of the most recent data from the Yahoo Finance website regarding the the CBA (Commonwealth Bank of Australia) and ANZ (Australia and New Zealand Banking Group Limited) stocks.

This ETL process creates a database in MongoDB containing two collections for both stocks, and two stock historical data csv files for both stocks and saves them in the location of the cloned repository.

![Database Structure](images/collections.PNG)

![Income Statements](images/income-statements.PNG)

## Tools/Packages used
- Python
  - datetime
  - splinter
  - BeautifulSoup
  - selenium import webdriver
  - pandas
  - pymongo
- MongoDB

## How to use
- Clone the respostiory to your Desktop.
- Pip install all the modules listed in ***Tools/Packages used***.
- open jupyter notebook in git bash and open the ***Complete ETL Process.Ipynb*** notebook.
- change the ```user``` variable on line 30.

![Change User name](images/change-user-name.PNG)

## Resouces used for this project
- Data Resources: Yahoo Finance
  1) ANZ: https://au.finance.yahoo.com/quote/ANZ.AX
  2) CBA: https://au.finance.yahoo.com/quote/CBA.AX
