# Movies-ETL- Extract, Transform, Load
## Project Overview
In this project, I've created an automated pipleine that takes in new data, performs the appropriate transformations, and loads the data into existing tables. I've refactored the code and created one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.


### Deliverable 1: Write an ETL Function to Read Three Data Files

In ETL_function_test.ipynb, Using knowledge of Python, Pandas, the ETL process, and code refactoring, I wrote a function that reads the three data files and creates three separate DataFrames.

### Deliverable 2: Extract and Transform the Wikipedia Data

In ETL_clean_wiki_movies.ipynb, Using knowledge of Python, Pandas, the ETL process, and code refactoring, I extracted and transformed the Wikipedia data so it can be merged with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, I used a try-except block to catch errors.

### Deliverable 3: Extract and Transform the Kaggle data

In ETL_clean_kaggle_data.ipynb, Using my knowledge of Python, Pandas, the ETL process, and code refactoring, I extracted and transformed the Kaggle metadata and MovieLens rating data, then converted the transformed data into separate DataFrames. Then, I merged the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, I merged the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.


### Deliverable 4: Create the Movie Database
In ETL_create_database.ipynb ,I used my knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
