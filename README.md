#  Movie Recommendation System

This project explores multiple recommendation algorithms using the **MovieLens 100K** dataset. It includes collaborative filtering methods and a Pixie-inspired graph-based recommendation system to generate personalized movie suggestions.

---

##  Dataset

The dataset used is the **MovieLens 100K** dataset, which includes:
- 943 users
- 1682 movies
- 100,000 ratings

Files used:
- `u.data`: user-movie ratings
- `u.item`: movie metadata
- `u.user`: user demographics

---

##  Features Implemented

###  User-Based Collaborative Filtering
- Recommends movies based on similar user preferences using **cosine similarity**.

###  Item-Based Collaborative Filtering
- Suggests similar movies based on user ratings for common movies.

###  Pixie-Inspired Graph-Based Random Walk
- Creates a bipartite graph (user-movie) and performs **random walks** to discover relevant movies based on visitation frequency.

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn (for similarity measures)
- Matplotlib (optional for visualizations)
- Jupyter Notebook

---



