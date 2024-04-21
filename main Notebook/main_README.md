# Movie Recommender with All Approaches

This project implements a movie recommendation system using various approaches including K-means clustering, DBSCAN, and Agglomerative Clustering. It leverages different techniques to process textual data associated with movies and recommends similar movies.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Approaches](#approaches)
- [K-means Clustering](#k-means-clustering)
- [DBSCAN](#dbscan)
- [Agglomerative Clustering](#agglomerative-clustering)


## Introduction
This project explores different clustering algorithms and cosine similarity to build a movie recommendation system. It preprocesses and cleans the movie data, then applies various clustering techniques to group similar movies together and recommends them to users.

## Prerequisites
Before running the code, ensure you have the following installed:
- Python (version 3.11.5)
- Required Python libraries: pandas, numpy, scikit-learn, nltk

## Installation

1. Clone the repository to your local machine:
2. Install the required Python libraries:

## Usage
1. Open the Python script file containing the code.
2. Run the script to execute the movie recommendation system.
3. Follow the prompts or input the desired movie title to receive recommendations.

## Data
The data used in this project includes the following CSV files:
- `movies.csv`: Contains information about movies including titles and genres.
- `tags.csv`: Contains user-provided tags for movies.
- `ratings.csv`: Contains user ratings for movies.
- `links.csv`: Contains links to other databases for each movie.

## Approaches

### K-means Clustering

The system applies K-means clustering on movie genres to group similar movies together. It then recommends movies within the same cluster based on cosine similarity.

### DBSCAN

DBSCAN clustering is applied to vectorized movie descriptions to find dense regions in the data space. It recommends movies from the same cluster as the input movie.

### Agglomerative Clustering

Agglomerative clustering is used to recursively merge similar clusters of movies based on their descriptions. It recommends movies from the same cluster as the input movie.

### Count Vectorizer and cosine similarity

Count vectorizer converts movies into vectors and then cosine similarity is used to find the most similar movies.It recommends the top 5 most similar movies.

