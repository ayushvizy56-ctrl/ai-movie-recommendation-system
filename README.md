# AI-Powered Movie Recommender System

An intelligent Movie Recommender System built using Machine Learning that suggests similar movies based on user selection. The application is integrated with the TMDB API to display movie posters, ratings, and descriptions in an interactive Streamlit web interface.

---

## Features

- Content-based movie recommendation  
- Suggests top 5 similar movies  
- Displays movie posters 
- Shows ratings  
- Provides short movie descriptions 
- Fast and responsive UI using Streamlit  

---

## Tech Stack

- Python 
- Pandas  
- Scikit-learn  
- Streamlit  
- TMDB API  

---

## How It Works

- Uses **cosine similarity** to find similar movies  
- Based on features like genres, keywords, cast, and crew  
- When a user selects a movie, the system recommends similar movies instantly  

---

## Project Structure

ai-powered-movie-recommender/

-app.py
- movie_dict.pkl
- similarity.pkl (not included)
- requirements.txt
- movie_recommender.ipynb

---

## Important Note

 'similarity.pkl' is **not uploaded** due to GitHub file size limitations (>25MB).

👉 To run the project locally, you need to generate it using the Jupyter Notebook:

``python
import pickle

pickle.dump(similarity, open('similarity.pkl', 'wb'))

