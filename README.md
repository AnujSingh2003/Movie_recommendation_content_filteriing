# Movie Recommendation System

## Introduction
This project is a movie recommendation system built using content-based filtering. It suggests movies to users based on the similarity of movies they have liked in the past.

## Features
- Content-based filtering for personalized movie recommendations
- Uses movie metadata for calculating similarity
- Simple and intuitive user interface

## Technologies Used
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning library for similarity calculations
- **Flask**: Web framework for creating the web application
- **HTML/CSS**: Frontend technologies for the user interface
- **Pickle**: Serialization library for saving and loading models

## Installation

### Prerequisites
- Python 3.x
- Pip (Python package installer)

### Steps
1. **Clone the repository:**
   ```sh
   git clone https://github.com/AnujSingh2003/Movie_recommendation_content_filteriing.git
   cd Movie_recommendation_content_filteriing
   ```

2. **Create a virtual environment and activate it:**
   ```sh
   python -m venv venv
   .\venv\Scripts\activate  # For Windows
   source venv/bin/activate # For Mac/Linux
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Ensure the model files are in the correct directory:**
   Make sure the `model` directory contains the necessary `.pkl` files:
   - `movie_list.pkl`
   - `similarity.pkl`

5. **Run the application:**
   ```sh
   python main.py
   ```

6. **Access the application:**
   Open your browser and go to `http://localhost:5000`


