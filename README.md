🎬 Movie Recommendation System
This project is a Movie Recommendation System built and run in Google Colab. It suggests movies similar to a user’s choice using TF-IDF Vectorization and Cosine Similarity for content matching.

📌 Features
Personalized recommendations based on movie similarity.

Handles minor spelling mistakes with difflib.

Simple implementation using Python libraries.

Runs entirely in Google Colab — no setup required on your PC.

🛠️ Libraries Used
python
Copy
Edit
import numpy as np
import pandas as pd
import difflib
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.metrics.pairwise import cosine_similarity
📂 Dataset
Uses a movie dataset containing titles, genres, and metadata (e.g., from Kaggle or TMDB). Upload your CSV file to Colab or mount Google Drive.

🚀 How It Works
Load dataset in Colab using pandas.

Convert text data (e.g., genres) into TF-IDF vectors.

Calculate similarity between all movies with cosine similarity.

Match user input using difflib.get_close_matches().

Return recommendations based on similarity scores.

📋 Running in Google Colab
Open the .ipynb file in Google Colab.

Upload the dataset

Run the cells in order.

Enter your favorite movie when prompted.
