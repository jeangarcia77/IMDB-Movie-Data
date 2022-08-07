# IMDB Movie Data

### Business Problem
I have been hired to process and analyze IMDB's extensive publicly-available dataset, supplement it with financial data from TMDB's API, convert the raw data into a MySQL database, and then use that database for extracting insights and recommendations on how to make a successful movie.

I will use a combination of machine-learning-model-based insights and hypothesis testing to extract insights for our stakeholders.
 
### Specifications/Constraints
- The stakeholder wants to focus on attributes of the movies themselves vs. the actors and directors connected to those movies.
- They only want to include information related to movies released in the United States.
- They also did not want to include movies released before the year 2000.
- The stakeholder is particularly interested in how the MPAA rating, genre(s), runtime, budget, and production companies influence movie revenue and user ratings.


## Part 1- Initial IMDB Data Processing.ipynb
### IMDB Movie Metadata
I will download fresh movie metadata from IMDB's public datasets and filter out movies that meet the stakeholder's requirements/constraints.

IMDB Provides Several Files with varied information for Movies, TV Shows, Made for TV Movies, etc.

Overview/Data Dictionary: https://www.imdb.com/interfaces/

Downloads page: https://datasets.imdbws.com/

Files to use:

- title.basics.tsv.gz
- title.ratings.tsv.gz
- title.akas.tsv.gz

## Part 2 - Extracting TMDB Data.ipynb (More to come)
### Supplement Data from The Movie Database (TMDB)'s
- I will extract MPAA rating and financial data for the movies using TMDB's API.

## Part 3 - MySQL Database Construction (More to come)
- I will then normalize all IMDB movie data into a proper MySQL database.

## Part 4 - Hypothesis Testing (More to come)
- I will then use the MySQL database to answer several hypotheses about movie success
