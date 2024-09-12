# 13-Crowdfunding_ETL
Crowdfunding_ETL - Extraction, Transformation, and Load

# 12-nosql-challenge
Crowdfunding_ETL - Extraction, Transformation, and Load
# Overview 
The purpose of this mini project it to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods to extract and transform data. After transforming the data, four CSV files and a table schema are created. Lastly, the four CSV files data into a Postgres database using SQL Alchemy
# Resources 
Jupyter notebook starter code
4 csv files
1 excel file

# Usage 
•	Extract the crowdfunding.xlsx Data
•	Create the Category and Subcategory DataFrames
•	Create the Campaign DataFrame
•	Create the Crowdfunding Database
•	Extract the contacts.xlsx Data.
•	Create the Contacts DataFrame
•	Extract, Transform, Load Using SQLAlchemy



# Dependencies
import pandas as pd
import numpy as np
pd.set_option('max_colwidth', 400)!pip install psycopg2
import psycopg2
from sqlalchemy import create_engine

# License
This project is licensed under the MIT License - see the LICENSE file for details.
