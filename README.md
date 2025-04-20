# Movie Recommender System

This project is a content-based movie recommender system that suggests similar movies based on user-selected input. It leverages cosine similarity on text-based features such as genre, director, cast, and description extracted from IMDb and Wikipedia data.

## Features

- Recommends movies similar to a selected title
- Utilizes text features to calculate similarity
- Clean visualization of results with poster images
- Lightweight and efficient for fast predictions

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Cosine Similarity
- IMDb & Wikipedia datasets

## How It Works

1. Data is preprocessed and merged from IMDb and Wikipedia sources.
2. Text features (like genre, plot, director, cast) are combined and vectorized.
3. Cosine similarity is calculated to find the closest matches to a selected movie.
4. Top similar movies are returned and displayed with titles and posters.

## Demo

A movie recommendation example:
```bash
Input: Inception  
→ Suggested: The Matrix, Interstellar, Shutter Island, etc.
```
