# Data Science Portfolio

A collection of machine learning and deep learning projects covering regression, classification, clustering, recommender systems, NLP, RNNs, CNNs, and semantic segmentation.

## Repository Structure

```text
.
├── projects/
├── shared/
├── archive/
├── requirements.txt
└── README.md

	•	projects/ contains the main portfolio projects
	•	shared/ contains shared assets, utilities, and supporting files
	•	archive/ contains older mixed or practice notebooks kept for reference

Projects

Machine Learning
	•	01_car_price_prediction
Predicting car prices using regression
	•	02_fuel_type_classification
Classifying fuel type using logistic regression
	•	03_student_score_prediction
Predicting student performance using multiple linear regression
	•	04_loan_approval_prediction
Predicting loan approval using multiple logistic regression
	•	05_employee_attrition_analysis
Comparing models such as logistic regression and random forest for employee attrition analysis
	•	06_customer_segmentation
Customer segmentation using K-Means clustering
	•	07_credit_card_fraud_detection
Fraud detection using Isolation Forest
	•	08_movie_recommender_collaborative
Collaborative filtering based recommendation system
	•	09_movie_recommender_content_based
Content-based recommendation system

Deep Learning / NLP / Computer Vision
	•	10_cnn_image_classification
CNN-based image classification
	•	11_emojify_lstm
Text-to-emoji prediction using embeddings / sequence modeling
	•	12_word_vectors_similarity_debiasing
Word vector similarity analysis and debiasing
	•	13_rnn_lstm_sequence_models
Sequence modeling with RNNs and LSTMs
	•	14_unet_segmentation
Semantic segmentation using U-Net
	•	15_dinosaur_name_generation_rnn
Character-level RNN for name generation
	•	16_resnet_from_scratch
ResNet implementation from scratch

Tools and Libraries

Some projects use:
	•	Python
	•	NumPy
	•	Pandas
	•	Matplotlib
	•	Scikit-learn
	•	TensorFlow / Keras

Notes
	•	This repository is being reorganized into a cleaner project-based portfolio structure.
	•	Some older mixed notebooks are stored in archive/ before being split into separate polished projects.

Next Improvements
	•	Add a dedicated README.md for each project
	•	Add sample results / plots for each project
	•	Standardize notebook naming and documentation
	•	Refactor reusable code into utility modules