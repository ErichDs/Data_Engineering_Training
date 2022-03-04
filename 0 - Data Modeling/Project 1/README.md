# Sparkify app

## Intro
 This project consists in an ETL process in order to get song files and log files from
the Music Stream App, Sparkify (not real), and load into generated tables for further
data analysis by the Sparkify analysts.

## Before run the scripts
 Make sure you have a postgres instance and python installed into your environment;
 You'll need the following python libs:
  - pandas
  - psycopg2
  - sql_queries
  - os and glob;

## How to use
 - 1:   Execute the "create_tables.py" file first, in order to get your database and tables all settled.
        This script will use the "sql_queries.py", already filled to get the tables structures, insert
        statements and queries used along the project.

 - 2:   Execute the "etl.py" to run the ETL process in order to populate you tables and get your data ready!

 * Obs.: The notebooks available in this project were used to develop the etl.py script and test the code;
         Make sure you have the "data" folder in the same folder with the scripts, otherwise, you'll need to point
         the path address to somewhere else (no one wants to do changes in the code now, right?).

## Testing
 You may want to run the cells in "test.ipynb" to evaluate your table structures, queries and the inserted data.
 
## Data files
 You'll find data files from songs under data/song_data and data files from logs under data/log_data.


 ### Enjoy!
