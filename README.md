# data_science_analysis_movies_dataset
The project performs data science analysis on the movies dataset collected from 'https://www.themoviedb.org/' site. The project works with .csv, .json, SQL dataset.

1]Data_Analysis_Presentation:It filter the dataset of 'movies_complete.csv' to answer the queries. 
2]Data_Import: Imports data from JSON filefrom "themoviedb.org" site using API. The JSON file is loaded into a pandas data frame.  
3]Data_Cleaning : It works with 'movies_metadata.csv'. Handles the stringified JSON columns and flatten nested columns. Converts the datatype to numeric. Replace unwanted info into missing values (nan). Removes duplicates and handles missing values. Cleaned data is stored in movies_clean.csv
4]Merging_Cleaning_Transforming: It will merge two data 'movies_clean.csv' and 'credits.csv'. After the two tables are joined,it answer the queries.
5]Pandas_SQL: Makes a connection with Sqlite3. Loads the data from dataframe into SQL database. Performs the SQL queries and Join queries using pandas. Uses 'some_movies.json' dataset
