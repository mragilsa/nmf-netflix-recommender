# NMF-Based Netflix Movie Recommender System

This repository implements a movie recommender system using Collaborative Filtering with Non-negative Matrix Factorization (NMF) on the Netflix Movie Rating Dataset.  

## Dataset
Netflix Movie Rating Dataset (from the Netflix Prize competition)

Source: [Kaggle – Netflix Movie Rating Dataset](https://www.kaggle.com/datasets/rishitjavia/netflix-movie-rating-dataset?select=Netflix_Dataset_Rating.csv)

Movie File Description:
- Movie File Contains Movie_ID, Name, Year

Rating File Description:
- Rating File Contains Movie_ID, User_ID, Rating (1 - 5)

## Evaluation Metrics
- RMSE: measures squared prediction error magnitude
- MAE: measures average absolute prediction error
- NDCG@10: evaluates ranking quality of top-10 recommendations

## Clone Repository
```bash
git clone https://github.com/mragilsa/nmf-netflix-recommender.git
```
```
cd nmf-netflix-recommender
```

## Generate Recommendations
Example usage to generate top-N movie recommendations for a user:
```python
recommend_movies(user_id=6, n_recommendations=5)
```
The function returns unseen movies ranked by predicted relevance for the selected user.
