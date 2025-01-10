# Data Modeling with Postgres
by Ricardo Cabanas 

# Project Description
This project creates a database called Sparkify from the information  provided by Udacity in data/data_songs and data/log_data. This information will be extracted, transformed, and loaded using etp.ipynb and etl.py will populate the database. create_tables.py and sql_queries.py will contain my table values and the connection to the database. I will be applying the star schema with one fact and four dimension tables.

# Star Schema
* Fact Table: songplays
* Dimension Tables: users, songs, artists, and time

![image](https://github.com/user-attachments/assets/5a12daa9-51c4-4538-b099-051c77946789)

# Implementation
- Jupyter Notebook
- Python
- Postgres

# ETL Pipeline 
For the ELT pipeline on etl.py I used the following functions:
- process_song_file (to process song files and transfer to the database)
- process_log_file (to process log files and transfer to the database)

# Run Scripts
To run etl.py and create_tables.py scripts I used the following command:
- %run etl.py
- %create_tables.py

