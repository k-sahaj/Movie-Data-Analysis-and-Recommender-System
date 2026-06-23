# Movie Analytics & Recommendation System

A comprehensive Data Science project that explores the movie industry through **Exploratory Data Analysis (EDA)**, **Machine Learning**, and **Recommendation Systems**. Using movie metadata, cast and crew information, budgets, revenues, ratings, and user interactions, this project uncovers industry insights, predicts movie performance, and builds personalized movie recommendation engines.

---

## Project Overview

The project is divided into two major components:

### Movie Data Analytics

This section focuses on understanding the movie industry through data. By analyzing movie metadata, cast and crew information, budgets, revenues, ratings, and genres, the project aims to:

- Discover historical trends in cinema
- Analyze factors affecting movie success and revenue
- Explore relationships between budgets, ratings, genres, and profitability
- Extract insights from cast and crew metadata
- Build predictive models for movie revenue and success

### Movie Recommendation Systems

This section focuses on building intelligent movie recommendation engines using multiple approaches:

- Popularity-Based Recommendation
- Content-Based Filtering
- Collaborative Filtering
- Hybrid Recommendation Systems

The goal is to provide personalized movie suggestions by leveraging both movie metadata and user behavior.

---

## 🗂 Repository Structure

```text
Movie Analytics & Recommendation System
│
├── Movie Data Analysis
│   ├── movies-data-analysis.ipynb
│   ├── movie+credits-data-analysis.ipynb
│   └── movie predictive models.ipynb
│
└── Movie Recommender System
    └── Recommender_Systems.ipynb
```

### Movie Data Analysis

| Notebook | Description |
|-----------|-------------|
| `movies-data-analysis.ipynb` | Exploratory analysis of movie metadata, ratings, budgets, revenues, genres, and historical trends |
| `movie+credits-data-analysis.ipynb` | Analysis of casts, crews, directors, actors, production companies, and movie credits |
| `movie predictive models.ipynb` | Machine learning models for movie revenue prediction and movie success classification |

### Movie Recommender System

| Notebook | Description |
|-----------|-------------|
| `Recommender_Systems.ipynb` | Implementation of popularity-based, content-based, collaborative filtering, and hybrid recommendation engines |

---

## Dataset

The project utilizes datasets collected from:

- MovieLens Dataset
- TMDB (The Movie Database) API
- Movie Metadata
- Credits Dataset (Cast & Crew Information)
- User Ratings Dataset

The datasets contain information such as:

- Movie titles
- Genres
- Ratings
- Vote counts
- Cast and crew details
- Budgets
- Revenues
- Keywords
- User interactions

---

## Methodology

### 1️⃣ Data Collection

- Acquired movie metadata from MovieLens and TMDB
- Gathered additional information through TMDB API endpoints
- Combined multiple datasets to create a richer analytical dataset

### 2️⃣ Data Cleaning & Preparation

- Missing value treatment
- Data type corrections
- Feature extraction and transformation
- Metadata normalization
- Parsing nested JSON-like fields
- Handling duplicate and inconsistent records

### 3️⃣ Exploratory Data Analysis (EDA)

Extensive analysis was conducted to uncover patterns and trends within the movie industry, including:

- Revenue and budget distributions
- Genre popularity analysis
- Highest-grossing movies
- Most profitable movies
- Cast and crew influence
- Production company trends
- Evolution of cinema over time
- Rating and vote behavior analysis

### 4️⃣ Feature Engineering

Features were engineered from:

- Cast information
- Crew information
- Genres
- Keywords
- Production companies
- Budget-related metrics
- Popularity indicators

### 5️⃣ Machine Learning

Two predictive models were developed:

#### Revenue Prediction

- Gradient Boosting Regressor
- Predicts movie revenue based on available metadata

#### Success Classification

- Gradient Boosting Classifier
- Classifies whether a movie is likely to be successful

Feature importance analysis was performed to identify the most influential variables affecting movie performance.

### 6️⃣ Recommendation Systems

Four recommendation engines were developed:

#### Popularity-Based Recommender

Ranks movies using:

- Vote counts
- Average ratings
- IMDB Weighted Rating Formula

#### Content-Based Recommender

Uses:

- Movie overviews
- Taglines
- Genres
- Keywords
- Cast information
- Crew information

to recommend similar movies.

#### Collaborative Filtering Recommender

Built using the Surprise Library and Singular Value Decomposition (SVD).

The model learns user preferences from historical ratings and predicts unseen movie ratings.

#### Hybrid Recommender

Combines:

- Content-Based Filtering
- Collaborative Filtering

to generate more personalized recommendations.

---

## Tech Stack

### Programming Language

- Python

### Data Analysis

- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-Learn
- Surprise

### Natural Language Processing

- NLTK

### Data Sources

- TMDB API
- MovieLens Dataset

### Development Environment

- Jupyter Notebook

---

## Results

### Predictive Models

| Model | Task | Performance |
|---------|---------|---------|
| Gradient Boosting Regressor | Revenue Prediction | R² Score: **0.78** |
| Gradient Boosting Classifier | Movie Success Prediction | Accuracy: **0.80** |

### Recommendation Systems

Successfully implemented:

✅ Popularity-Based Recommender

✅ Content-Based Recommender

✅ Metadata-Based Recommender

✅ Collaborative Filtering (SVD)

✅ Hybrid Recommendation Engine

The hybrid recommender delivered the most personalized recommendations by combining user preferences with movie metadata.

---

## Key Insights

Some notable findings from the analysis include:

- Higher-budget films generally generate higher revenues, although exceptions exist.
- Popular actors and directors often contribute significantly to commercial success.
- Certain genres consistently outperform others in terms of profitability.
- Vote count is often a stronger indicator of popularity than average rating alone.
- Metadata-based recommendation systems provide better personalization than simple popularity rankings.
- Hybrid recommendation systems achieve the most balanced recommendation quality.

---

## Future Enhancements

- Deploy recommendation system as a web application
- Build an interactive Streamlit dashboard
- Integrate real-time TMDB API updates
- Experiment with XGBoost and LightGBM models
- Incorporate deep learning-based recommendation techniques
- Add model explainability using SHAP values
- Develop user-facing recommendation interfaces

---

## Project Highlights

- End-to-end Data Science workflow
- Real-world movie industry dataset
- Extensive Exploratory Data Analysis
- Feature Engineering
- Predictive Machine Learning Models
- Multiple Recommendation Algorithms
- Personalized Movie Recommendation Engine
- Business and entertainment industry insights

---


---

## ⭐ If you found this project useful, consider giving it a star!
