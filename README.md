# Exploring Movie Trends: Popular Genres, Ratings, and Revenue Analysis

## Overview
This project analyzes a movie dataset to uncover trends in genres, ratings, and revenue. By exploring relationships between revenue and ratings, identifying the most popular genres, and understanding changes in movie ratings over time, this project provides valuable insights into the movie industry.

## Objectives
- Identify the most popular movie genres.
- Analyze how movie ratings have evolved over time.
- Highlight the top-grossing movies in the dataset.
- Determine whether there is a correlation between revenue and ratings.

## Tools & Technologies
- **Programming Language**: Python
- **Libraries Used**:
  - Data Analysis: `Pandas`, `NumPy`
  - Visualization: `Matplotlib`, `Seaborn`
- **Environment**: Jupyter Notebook

## Dataset
- **Source**: The dataset was downloaded from Kaggle.

- **Key Features**:
  - **Genre**: The genre(s) of each movie (e.g., Action, Drama).
  - **Released_Year**: The year the movie was released.
  - **IMDB_Rating**: The rating of the movie on a scale of 0 to 10.
  - **Gross**: The gross revenue generated by the movie.
  - **Series_Title**: The title of the movie.

## Workflow
1. **Data Cleaning and Preprocessing**:
   - Removed missing or invalid data from essential columns like `Gross` and `IMDB_Rating`.
   - Converted columns to appropriate data types (e.g., numeric conversion for `Gross`).

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed the most common genres.
   - Visualized the evolution of ratings over time.
   - Identified the highest-grossing movies.
   - Explored the relationship between revenue and ratings.

3. **Visualization**:
   - Created bar plots, line plots, and scatter plots for insights.

## Results
- **Most Popular Genres**:  
  Drama, Action, and Crime were the most common genres in the dataset.

- **Ratings Over Time**:  
  Average movie ratings have remained stable over the years, with minor fluctuations.

- **Top-Grossing Movies**:  
  Movies like *The Dark Knight* and *Inception* topped the revenue charts, with gross revenues exceeding $500M.

- **Revenue-Rating Correlation**:  
  A weak positive correlation was found between revenue and ratings, indicating that higher ratings do not guarantee higher revenue.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://
