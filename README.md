# Movies-Recommendation-System

## Introduction:
It is a content-based recommendation system. A content-based recommender works on the data we collect from the user.
This recommender works by taking a movie title as an input and recommends 5 similar movies to it.
## Approach:
I used bag of words (CountVectorizer) for text vectorization and cosine distance to determine the similarity of vectors.
1. The movies records are considered as vectors.
2. Using cosine distance, closest vectors are compared.
3. The closest 5 vectors to the user input are displayed as an output to the user.

The web interface is created using streamlit, an open-source app framework in Python.

## Dataset: 
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
