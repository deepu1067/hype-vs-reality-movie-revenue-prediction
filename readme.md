# 🎬 Movie Data Scraper and Sentiment Analysis

Welcome to the Movie Data Scraper and Sentiment Analysis project! This project aims to gather detailed movie information and analyze sentiments from user comments. Below is a step-by-step overview of the process:

## 📂 Data Collection

1. **IMDB Movie List**: We started by gathering the `movie.csv` file from the IMDB movie list.
2. **OMDB API**: Using the `movie.csv`, we fetched detailed information from the OMDB API. Check the `obdb.ipynb` file for the implementation. This step generates the `movie_info.csv` file.

## 📊 Sentiment Analysis

3. **Sentiment Data**: We converted sentiment CSV files to match the movies and merged them with `movies.csv` and sentiment results. The number of negative and positive comments are counted and shown. Check `sentiments_movies.csv` for details.

## 🔄 Data Merging and Cleaning

4. **Merging Files**: We merged the sentiment data with `movies_info.csv` to create a new merged file.
5. **Data Cleaning**: The dataset was cleaned to remove null or empty values.

## 📁 Files Overview

- `movie.csv`: Initial movie list from IMDB.
- `movie_info.csv`: Detailed movie information from OMDB.
- `sentiments_movies.csv`: Sentiment analysis results merged with movie data.
- `final_merged.csv`: Final cleaned and merged dataset.

## 📈 Results

The final dataset provides a comprehensive view of movie details along with sentiment analysis, helping in understanding the audience's perception of each movie.

Feel free to explore the notebooks and datasets to gain more insights!

Happy Analyzing! 🎉
