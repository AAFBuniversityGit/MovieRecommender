# Movie Recommender

Welcome to the Movie Recommender project! This repository contains a machine learning model built using ML.NET that predicts the rating a user is likely to give to a particular movie (on a scale of 1 to 5). Based on these predictions, the system recommends movies that exceed a certain rating threshold, ensuring that users receive suggestions they are more likely to enjoy.

## Features

- Predicts movie ratings based on user and movie data.
- Recommends movies that meet or exceed a defined rating threshold.
- Built with ML.NET using Matrix Factorization for collaborative filtering.

## How It Works

The model is trained using a dataset of user-movie ratings, where each entry represents a user's rating for a particular movie. The model uses this data to predict future ratings for movies that a user has not yet rated. If the predicted rating exceeds a certain threshold (e.g., 3.5), the movie is recommended to the user.

## Getting Started

To get started, follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/AAFBuniversityGit/MovieRecommender.git
