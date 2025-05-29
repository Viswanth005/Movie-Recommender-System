# Movie-Recommender-System

A simple movie recommender that suggests similar movies based on their content.
Give it a movie title, and it will recommend 10 similar movies based on plot, genres, and keywords.

Setup: 
  1. Install required packages: pip install -r requirements.txt
  2. Make sure you have the dataset files in a tmdb/ folder:
       -> tmdb_5000_credits.csv
       -> tmdb_5000_movies.csv

How it works:
  1. Combines movie features (plot + genres + keywords) into text.
  2. Uses TF-IDF to convert text into numbers.
  3. Calculates similarity between movies.
  4. Returns the 10 most similar movies.
