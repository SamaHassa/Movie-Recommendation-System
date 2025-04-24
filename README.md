# Movie-Recommendation-System
Overview
This repository contains a Jupyter Notebook implementation of a content-based movie recommendation system. The system uses movie metadata (genres, overviews, keywords, and credits) to suggest similar movies based on cosine similarity of TF-IDF vectorized features.
Features
Data preprocessing and cleaning of movie metadata

Text processing using NLTK's SnowballStemmer

TF-IDF vectorization of movie tags (combined features)

Cosine similarity calculation between movies

Interactive recommendation function that:

Takes a movie title as input

Displays the poster of the requested movie

Shows recommended movies with their posters

Visualization of recommendations in a grid layout

Requirements
Python 3.x

Jupyter Notebook

Required Python packages:

pandas

numpy

matplotlib

seaborn

nltk

scikit-learn

scikit-image

pickle

Dataset
The system uses a movies dataset (movies.csv) containing:

Movie titles and IDs

Genres, overviews, and keywords

Cast and crew information (credits)

Popularity metrics and vote information

Poster and backdrop image paths

How to Use
Clone this repository

Install required packages using pip install -r requirements.txt

Download NLTK's SnowballStemmer data by running nltk.download('stopwords') in a Python shell

Place your movies.csv file in the project directory

Open and run the Jupyter Notebook movie-recommendation-system.ipynb

Usage Example
python
# Get recommendations for a movie
get_recommendations("Bullet Train")
Output
The function will display:

The poster of the requested movie

A grid of recommended movie posters with their titles

Customization
You can modify:

The number of recommendations returned

The weighting of different features (genres, keywords, etc.)

The visualization style of the recommendations

Future Improvements
Implement collaborative filtering for hybrid recommendations

Add user rating integration

Create a web interface for the recommendation system

Optimize for larger datasets

License
This project is open-source and available under the MIT License.

Acknowledgments
Dataset from TMDB (The Movie Database)

scikit-learn for machine learning tools

NLTK for text processing

![image](https://github.com/user-attachments/assets/2df91e46-0a89-4bb7-bbd8-00dccf5b6297)
