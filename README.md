# Problem Statement
Collect all updated data of Tadawul Market from the following link:https://www.tadawul.com.sa/wps/portal/tadawul/markets/equities/market-watch/market-watch-today?locale=en

·       Collect all the companies and the values of each and store the data in PostgreSQL database. Please note that you should save each company with its category ;for example, SARCO under Energy cat.

-Read the stored data from database and show it as a table .

2.       From the link below, you need to store the Excel file in PostgreSQL and then use the stored data to build dashboard to show useful insights.:

  
  https://data.gov.sa/Data/ar/dataset/field-of-study-2013-2018

# Solution & Assumptions

**There are two jupyter notebook
- Tadawul build AutoScraper rules
- Tadawul_build Db

Tadawul build AutoScraper rules
- build the AutoScraper rule to  Collect all updated data of Tadawul Market and save it into json file.
Tadawul_build Db
- Loading a json file and use it to build a DataFrame and save it to PostgreSQL


install necessary packages.

pip install autoscraper

The PostgreSQL Databases:
-TadawlDb
It contains files collected from Tadawul

-Higher_EducationDb
It contains files collected from https://data.gov.sa/Data/ar/dataset/field-of-study-2013-2018
