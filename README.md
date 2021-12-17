# Movies-ETL
### Module 8 of UC Berkeley's Data Analytics and Visualization Bootcamp - Databases, ETL

#### Purpose:
This module introduced the basic principles of the extract, transform, and load (ETL) process of a data science pipeline. Using data sets downloaded from Kaggle and Wikipedia, a pipeline was built to clean, parse, and merge data from three different files into a clean, usable data set, which was finally exported to a database.


### Data Sources:
**Wikipedia**
- movies on Wikipedia from 1990 to 2018 (already extracted and formatted as json)
- wikipedia-movies.json data set downloaded from bootcamp resources for this module

**Kaggle**
- metadata from The Movies Database(https://www.themoviedb.org/)
- ratings data from MovieLens
- download zip at https://www.kaggle.com/rounakbanik/the-movies-dataset/download

*Note: Due the large size of the original Kaggle data sets, a smaller data set was created for grading this assignment/testing code. Corresponding files are:*
- kaggle_sample.csv (a random sampling of 1000 entries from movies_metadata.csv)
- ratings_sample.csv (subset of ratings.csv that contains only ratings for movies in kaggle_sample.csv file)


---

### Module exercises included
- Downloading and extracting data from public sources
- Transforming data
	- Data exploration
	- Using functions
	- Converting data types
	- Cleaning
	- Parsing
	- Merging data from different sources
- Regular expressions
- Exporting cleaned data to PostgreSQL

*Note: Module exercises were completed with the full Kaggle data set. The uploaded jupyter notebook for Module 8 exercises was edited to run on the smaller sample data set.*

---

### Module 8 Challenge

*Note: Challenge files were originally run with the full Kaggle data set. Current outputs displayed in the notebooks below reflect this. However, the code has been edited to run with the smaller sample data sets for code testing.*

**Files for grading:**
- ETL_function_test.ipynb
- ETL_clean_wiki_movies.ipynb
- ETL_clean_kaggle_data.ipynb
- ETL_create_database.ipynb
- movies_query.png
- ratings_query.png


