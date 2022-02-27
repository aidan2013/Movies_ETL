# Movies_ETL
This analysis is to extract, transform and load raw data from Wikipedia movie data, Kaggle metadata and MovieLens ratings into PgAdmin using PostgreSQL.

### Extract:

Extract the data from movies_metadata.csv, ratings.csv, and wikipedia-movies.json.

![image](https://user-images.githubusercontent.com/91445591/155889734-3c033550-940d-4c91-b41d-60c6ed159f69.png)

### Transform:

Clean the data from movies_metadata.csv, ratings.csv, and wikipedia-movies.json.

![image](https://user-images.githubusercontent.com/91445591/155889786-83181973-45e0-4e73-8dd4-8fbc88d3173c.png)

### Load: 

Create the connection to the PostgreSQL database, then add the movies_df DataFrame to a SQL database.

![image](https://user-images.githubusercontent.com/91445591/155889820-86e1f463-9945-4244-ab32-d99d7bab2b31.png)

- Verify the movies table was successfully created in the PostgreSQL database.

![image](https://user-images.githubusercontent.com/91445591/155890131-609ed630-9572-4664-bf54-b59a89080e53.png)

![image](https://user-images.githubusercontent.com/91445591/155890150-e0955948-4c30-4828-9d18-7ad12b1d736a.png)

- Verify the ratings table was successfully created in the PostgreSQL database.

![image](https://user-images.githubusercontent.com/91445591/155890196-d473f6ed-d00b-4c4b-b687-ee65bb80dd86.png)

![image](https://user-images.githubusercontent.com/91445591/155890172-afbdd716-32a7-4339-a5d4-f1eb10a9eef1.png)
