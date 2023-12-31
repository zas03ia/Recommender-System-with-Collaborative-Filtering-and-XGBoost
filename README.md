# Recommender-System-with-Collaborative-Filtering-and-XGBoost
Overview
Data Exploration: The code starts by loading the movie ratings dataset (ratings.csv) and creating a heatmap to visualize user-movie ratings.
Collaborative Filtering with SVD: Singular Value Decomposition (SVD) is applied to the dataset using the Surprise library. The code then computes user and movie averages for further analysis.
Cosine Similarity: User and movie similarities are calculated using cosine similarity, enhancing the collaborative filtering predictions.
XGBoost Model: The collaborative filtering predictions, along with user and movie averages, are used as features to train an XGBoost regression model. The model is evaluated on the test set, and performance metrics such as RMSE and MAPE are calculated.

Visualizations: Bar charts depict average ratings by user and movie, and the distribution of movie ratings is visualized. Training curves for the XGBoost model and residual plots provide insights into the model's performance.

Results: The final results include test metrics (RMSE and MAPE) and visualizations to understand the accuracy of the recommendation system.
Dependencies
pandas
numpy
scikit-surprise
scipy
scikit-learn
xgboost
matplotlib
seaborn

Inspiration: https://towardsdatascience.com/how-to-build-a-movie-recommendation-system-67e321339109
