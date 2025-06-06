# IMDB Movie Analysis 

[View the Rendered HTML Report](https://htmlpreview.github.io/?https://github.com/trannnle/R-Projects/blob/main/IMDB%20Movie%20Analysis/IMDB_Movie_Analysis.html)


## Tech Stack

- **Language**: R  
- **Environment**: RStudio  
- **Workflow**: R Markdown (`.Rmd`)  
- **Data Manipulation**: `tidyverse`, `dplyr`  
- **Visualization**: `ggplot2`  
- **Rendering**: `knitr`, `html_document`, `html_notebook`
- **Packages**:
  - `tidyverse`
  - `ggplot2`
  - `dplyr`
  - `knitr`


## Introduction

This project explores the IMDB-5000 movie dataset (IMDB_movies.csv) using R. The analysis focuses on identifying trends in movie revenue, IMDB scores, and content ratings using tidy data principles and visualizations.

- Load and inspect the IMDB movie dataset
- Clean and transform data using `dplyr` and pipes
- Explore revenue patterns across content ratings
- Visualize the relationship between IMDB score and movie revenue
- Analyze director-specific performance (e.g., James Cameron)
- Apply `ggplot2` to create informative scatter plots with smoothing

- **File**: `datasets/IMDB_movies.csv`
- **Source**: Provided via course materials
- **Size**: 3,889 rows × 25 columns
- **Variables**:
  - `movie_title`: Title of the movie  
  - `director_name`: Name of the director  
  - `gross`: Total box office revenue (USD)  
  - `budget`: Estimated production budget (USD)  
  - `country`: Country of production  
  - `title_year`: Year the movie was released  
  - `imdb_score`: IMDB rating score  
  - `language`: Primary language of the film  
  - `duration`: Length of the movie (in minutes)  
  - `genres`: Pipe-separated list of genres (e.g., `Action|Adventure`)  
  - `content_rating`: Official content rating (e.g., `PG-13`, `R`)  
  - `aspect_ratio`: Aspect ratio of the film  
  - `color`: Indicates if the film is in color or black-and-white  
  - `plot_keywords`: Key plot terms (pipe-separated)  
  - `movie_facebook_likes`: Number of likes on the movie's Facebook page  
  - `director_facebook_likes`: Number of likes on the director's Facebook page  
  - `cast_total_facebook_likes`: Combined likes of all actors in the cast  
  - `facenumber_in_poster`: Number of faces visible in the poster  
  - `actor_1_facebook_likes`: Facebook likes of the lead actor  
  - `actor_1_name`: Name of the lead actor  
  - `actor_2_facebook_likes`: Facebook likes of the second actor  
  - `actor_2_name`: Name of the second actor  
  - `num_user_for_reviews`: Number of user reviews on IMDB  
  - `num_critic_for_reviews`: Number of critic reviews on IMDB  
  - `num_voted_users`: Number of users who voted/rated the movie  
