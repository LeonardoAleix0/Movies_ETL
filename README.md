<<<<<<< TO >>>>>>>
# Movies-ETL
=======
# **Movies_ETL**

## Overview of Project

This project’s objective is to extract, transform and load using regular expressions to parse data. After cleaning the data, maintaining its consistency and integrity, the data will be transferred from one database to another. The deliverables for this project are:

*	Write an ETL function to read three data files.
* 	Transform the data sources to transform it into one data set.
*	Create a clean database and load it in SQL.
*	

## Data Source Information
The data source used in this project is composed by two CSV files and one JSON file. 


## Software
Python 3.7.7, Jupyter Notebook and PostgreSQL. 


## Results 

### Write an ETL function to read three data files.
The Wikipedia data used for this project was stored in a JavaScript Object Notation (JSON) file, that will later  be compiled with two CSV files. The JSON file was extracted and loaded as a list of dictionaries, the list of records was inspected to confirm that the dataset is usable. The CSV files were downloaded from Kaggle website, the files were inspected and confirmed that they were good for analysis.


### Transform the data sources to transform it into one data set. 
Due to the high number of columns the Wikipedia file was converted into a list of columns to verify and remove columns that were not necessary for this analysis. Throughout each cycle of action to clean this dataset, the file was saved under a new variable instead starting the whole process in case a mistake is made.
Using list comprehensions and Regex, rows with no values were removed and currency values were formatted.

### Create a clean database and load it in SQL.
A database was created at PgAdmin to load the cleaned file. To import the database, a database_engine was created to allow communication between Pandas and SQL server.


## Summary
The ETL process in this project allowed the extraction of different datasets from different sources. After transforming the data into a clean dataset, the data was ready for querying and analysis, allowing its end users to have a better view of the information and consequently making better decisions. 

>>>>>>> be16e9d2a90ac97e8649ae0a13089c43b525553a
