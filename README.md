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

## Repository Structure

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
[Link](https://grouplens.org/datasets/movielens/)

- MovieLens Dataset
- TMDB (The Movie Database) API
- Movie Metadata
- Credits Dataset (Cast & Crew Information)
- User Ratings Dataset
  
---

## Approach 

The problem was divided into several steps:

1. **Data Collection:** Data was collected from the MovieLens website and through a script that queried for data from various TMDB Endpoints.
2. **Data Wrangling:** The datasets were uploaded to a dataframe and explored. Null values were filled in wherever appropriate and polluted values were discarded or wrangled.
3. **EDA:** Extensive data visualisation and summary statistics were used to extract insights and pattern from the various datasets. The history, facts and trivia behind movies were narrated through data.
4. **Machine Learning:** Gradient Boosting Classifer and Regressor were trained on our feature engineered dataset to predict movie success and revenue respectively. Their feature importances were noted to gain insights into what factors influence the revenues of a movie relative to budget.
5. **Recommendation Systems:** Four different recommendation systems were built using various ideas and algorithms such as IMDB's Weighted Rating, Content Based Filtering and Collaborative Filtering.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

- Scikit-Learn
- Surprise
- NLTK

- TMDB API
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

**Result-**
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

## Project Highlights

- Real-world movie industry dataset
- Extensive Exploratory Data Analysis
- Predictive Machine Learning Models
- Multiple Recommendation Algorithms
- Business and entertainment industry insights

---

