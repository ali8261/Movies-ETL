# Movies-ETL

Project Overview

In this project we are creating an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data. It then performs the appropriate transformations and loads the data into an existing PostgreSQL database
For this analysis, we used the following breakdown:

1.	write an ETL function to read three data files,
2.	extract and transform the Wikipedia data,
3.	extract and transform the Kaggle and rating data,
4.	load the data to a PostgreSQL Movie Database.

Resources

•	Data Source: wikipedia-movies.json, movies_metadata.csv, ratings.csv

Results

1.	Write an ETL function to read three data files
The function takes the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates three separate DataFrames.
2.	Extract and Transform the Wikipedia data
Filtered out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.
3.	Extract and Transform the Kaggle and rating data 
Again, we consolidated the redundant data, removed the duplicates, formatted and grouped the data.
The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.
4.	Load the data to a PostgreSQL Movie Database
