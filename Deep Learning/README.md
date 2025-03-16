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

Hand digit recognition:

  1) Overview:
              This project focuses on recognizing hand signs representing digits (0-5) using a Convolutional Neural Network (CNN). The goal is to classify hand gestures accurately for applications like gesture-controlled systems and assistive tools.

  2) Model Architecture:
              Conv2D → ReLU → MaxPooling2D → Conv2D → ReLU → MaxPooling2D → Flatten → Dense
              The CNN extracts spatial features, reduces dimensionality, and classifies digits via a fully connected layer.

  3) Training Details:
              Loss: Categorical Crossentropy
              Optimizer: Adam 
              Metrics: Accuracy
              Input: Preprocessed and normalized hand sign images

  4) Results:
              Achieved and accuracy of 80%+ in classifying digits, with similar performance on unseen data using this simple model.