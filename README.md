# Movie Recommendation System

This project implements a **Movie Recommendation System** using both **collaborative filtering** and **content-based filtering** techniques. The goal of this project is to recommend movies to users based on their preferences, past ratings, and movie attributes such as genre, description, etc.

## Features

- **Content-Based Filtering**: Utilizes **TF-IDF** vectorization and **cosine similarity** to recommend movies that are similar in terms of metadata (e.g., genre, descriptions).

## Libraries Used

- **Pandas**: For data loading, manipulation, and preprocessing.
- **Scikit-learn**: For implementing content-based filtering, including TF-IDF vectorization and cosine similarity.
- **NumPy**: For efficient numerical computations.

## Dataset

This project uses the [MovieLens dataset](https://grouplens.org/datasets/movielens/) (or another dataset depending on your project). The dataset includes information such as movie titles, genres, and user ratings.
