Collaborative Filtering Recommendation System
  This project develops a collaborative filtering recommendation system using matrix factorization to predict user ratings for movies based on historical user-item interactions. The system recommends movies tailored to users' preferences by leveraging patterns from similar users.

  Evaluation: The model is assessed using Root Mean Squared Error (RMSE).
  Future Improvements: Incorporate additional features (e.g., movie genres), experiment with varying latent factors, and optimize learning rates to enhance performance.

Content-Based Filtering Recommendation System
  This project implements a content-based filtering system that recommends movies based on users' past ratings and preferences. It leverages user and movie features to improve recommendation accuracy.

  Personalized Recommendations: Suggests movies aligned with users' historical ratings and preferences.

  Feature Engineering: Includes average user ratings per genre, average movie ratings, and the number of ratings per movie.

  Neural Network Architecture: Employs two neural networks—one for user features and one for movie features—with regularization and batch normalization to boost performance. The final prediction is derived from the dot product of the network outputs.

  Top-N Recommendations: A get_top_n_recommendations function retrieves the top N movie recommendations for a user, sorted by predicted ratings.

Hand Digit Recognition
  This project focuses on classifying hand signs representing digits (0–5) using a Convolutional Neural Network (CNN). The aim is to accurately recognize hand gestures for applications like gesture-based control systems and assistive technologies.

  Model Architecture: The CNN consists of Conv2D → ReLU → MaxPooling2D → Conv2D → ReLU → MaxPooling2D → Flatten → Dense layers, extracting spatial features and classifying digits through a fully connected layer.
  Training Details:

  Loss: Categorical Crossentropy
  Optimizer: Adam
  Metric: Accuracy
  Input: Preprocessed and normalized hand sign images


  Results: Achieved over 80% accuracy on both training and unseen data, demonstrating robust performance with a simple model.

ResNet-50 Implementation:
  This project implements a ResNet-50 model from scratch. The current dataset is too small for such a deep architecture, so training on a larger dataset is planned to improve performance.
  
U-Net for Semantic Segmentation:
  This project builds a U-Net model from scratch and trains it on the Cityscapes dataset for semantic segmentation. The model is currently underperforming due to limited training (3 epochs). Extended training is expected to significantly improve results.