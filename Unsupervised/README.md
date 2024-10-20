KMeans Clustering:
  1) The dataset contains customer information who had visited a mall
  2) The first part of the notebook contains code for EDA (cleaning dataset, identifying outliers). But the dataset used appears to be clean.
  3) Unwanted columns were dropped and then the data was scaled.
  4) Inertia and Silhouette scores were plotted against clusters to determine the optimal cluster value.
  5) A scatterplot was plotted (Age vs Income) to visualize clusters.
  6) Evaluation: This doesn't seem to be a great model as there seem to be overlaps of clusters as depicted in the scatterplot and by looking at the silhouette score.

Isolation Forest:
  1) The dataset contains transaction information of credit card
  2) The first part of the notebook contains code for EDA (cleaning dataset, identifying outliers, ensuring features were gaussian). But the dataset used appears to be fairly clean.
  3) Unwanted columns were dropped and then the data was scaled.
  4) An isolation forest alogorithm was implemented to detect and classify any anomalous transactions.
  5) The model was then evaluated using a confusion matrix, classification report and the ROC Curve, which suggests that the model was fairly competent.

Collaborative Filtering:

  1) This project implements a collaborative filtering recommendation system using matrix factorization. 2) The algorithm predicts user ratings for movies based on historical user-item interactions. It aims to recommend movies that users are likely to enjoy based on similar users' preferences.
  3) The model was evaluated using the RMSE function.
  4) Future Improvements: We could Utilize additional features like genres, experiment with different numbers of latent factors and learning rates for better performance, etc.


Content Based Filtering:

This project implements a content-based filtering recommendation system that predicts top movies for users based on their past ratings and preferences. The model utilizes various user and movie features to enhance the recommendation accuracy.

  1) Personalized Recommendations: The system suggests movies that users are likely to enjoy, based on their historical ratings and preferences.
  2) Feature Engineering:
                Average rating by user for each genre.
                Average rating of movies.
                Number of ratings received for each movie.
  3) Neural Network Architecture:
                Two separate neural networks are created for user and movie features.
                Techniques such as regularization and batch normalization are implemented to improve model performance.
                The final prediction is made by calculating the dot product of the outputs from the user and movie networks.
  4) Top-N Recommendations:
                A function get_top_n_recommendations retrieves the top N recommended movies for a specified user, sorted by predicted ratings.