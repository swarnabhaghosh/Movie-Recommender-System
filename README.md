# Movie Recommender System

A Python-based movie recommendation system that leverages content-based filtering to suggest movies based on user preferences. The system utilizes metadata such as movie genres, titles, and tags to recommend similar movies.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation Guide](#installation-guide)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

This project implements a movie recommendation system using content-based filtering techniques. By analyzing movie metadata, the system suggests movies that are similar to a given movie, enhancing the user experience by providing personalized recommendations.

## Features

- **Content-Based Filtering**: Recommends movies based on metadata such as genres, titles, and tags.
- **Similarity Calculation**: Utilizes cosine similarity to determine the closeness between movies.
- **User-Friendly Interface**: Provides an interactive interface for users to input their preferences and receive recommendations.

## Installation Guide

To set up the project locally, follow these steps:

1. **Clone the Repository**:

```
git clone https://github.com/swarnabhaghosh/Movie-Recommender-System.git
cd Movie-Recommender-System

```
2. **Create and Activate a Virtual Environment**:

```
python -m venv movieenv
source movieenv/bin/activate  # On Windows, use `movieenv\Scripts\activate`

```
3. **Install Dependencies**:

```
pip install -r requirements.txt

```

## Usage

To run the recommendation system:

1. **Launch the Application**:

```
streamlit run app.py

```
2. **Access the Application**:

Open your web browser and navigate to `http://localhost:8501` to interact with the movie recommender.

## Project Structure

The repository contains the following key files and directories:

- `app.py`: Main application file to run the Streamlit app.
- `movie-recommender-system.ipynb`: Jupyter notebook with the core recommendation logic.
- `requirements.txt`: List of Python packages required for the project.
- `movie_list.pkl`: Serialized list of movies for quick access.
- `similarity.pkl`: Serialized similarity matrix for efficient computation.
- `tmdb_5000_credits.csv`: Dataset containing movie credits information.
- `tmdb_5000_movies.csv`: Dataset containing movie metadata.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- **Datasets**: The movie metadata and credits information are sourced from The Movie Database (TMDb).
- **Libraries**: Utilizes libraries such as `pandas`, `numpy`, `scikit-learn`, and `streamlit` for data processing and application development.
