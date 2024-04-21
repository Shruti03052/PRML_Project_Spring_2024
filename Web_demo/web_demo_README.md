# Movie Recommendation System

This project implements a movie recommendation system using content-based filtering techniques. It analyzes the textual data associated with movies, such as genres and user-provided tags, to recommend similar movies based on their descriptions.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Algorithm](#algorithm)
- [Results](#results)
- [WebInterface](#Webinterface)



## Introduction

This recommendation system is built using Python and several libraries such as pandas, scikit-learn, and nltk. It employs natural language processing techniques to process and analyze textual data associated with movies. The system suggests similar movies based on their descriptions, combining genres and user-provided tags.

## Prerequisites

Before running the code, ensure you have the following installed:

- Python (version 3.x)
- Jupyter Notebook or any Python IDE
- Required Python libraries: pandas, numpy, scikit-learn, nltk

## Installation

1. Clone the repository to your local machine:
2. Install the required Python libraries:
pandas
numpy
re
sklearn
nltk

## Usage

1. Open the Jupyter Notebook file `movie_recommendation_system.ipynb`.
2. Execute the code cells in the notebook step by step.
3. Provide the necessary input data (movie titles) to get recommendations.

## Data
The data used in this project consists of four CSV files:
- `movies.csv`: Contains information about movies including titles and genres.
- `tags.csv`: Contains user-provided tags for movies.
- `ratings.csv`: Contains user ratings for movies.
- `links.csv`: Contains links to other databases for each movie.

## Algorithm
The recommendation system uses content-based filtering techniques, specifically cosine similarity, to recommend movies. It processes textual data associated with movies, such as genres and tags, to compute similarity scores between movies. Based on these scores, it recommends similar movies to the input query.

## Results
The system provides recommendations based on the input movie title. It returns a list of top similar movies based on their descriptions.

## Web Interface
For enhanced user experience we have developed a website where user can interact with the recommender system seamlessly
app.py provides the code needed to build the website.

Here is the link to the github repository for building website
[Link to the repository]()
## Usage of app.py
For running app.py user can provide following commands
- streamlit run app.py




