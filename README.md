# MOVIE RECOMMENDER SYSTEM WITH AUTOENCODERS
This repository hosts a sophisticated movie recommender system that uses deep learning techniques, specifically autoencoders. The system aims to provide personalized movie recommendations to users, enhancing their overall viewing experience.
## Dataset
- Link: [MovieLens 1M Dataset](https://files.grouplens.org/datasets/movielens/ml-1m.zip)
- The dataset contains 1,000,209 ratings from 6,040 unique users for 3,706 unique movies.
- Columns include UserID, MovieID, Rating, Timestamp, Title, and Genres.
## Data Preprocessing:
- Checked for missing values and duplicates.
- Integrated rating and movie datasets.
- Filtered movies with ratings greater than 25.
- Extracted movie release year and standardized ratings.
## Exploratory Data Analysis (EDA):
- Visualized rating distributions per user and movie.
- Explored average ratings per movie and user.
- Analyzed movie genre distributions.
## Model Architecture: Autoencoder
- Input, Encoding, Bottleneck, Decoding, and Output layers.
- ReLU activation for encoding/decoding layers.
## Training and Evaluation:
- Data split into 80% training and 20% test sets.
- Trained using Adam optimizer and MSE as the loss function.
- Achieved an MSE value of approximately 0.0557 on the test set.
## Recommendation System:
- User embeddings capture preferences.
- Nearest Neighbors model with cosine similarity identifies similar users.
- Recommendation function suggests personalized movies for a target user.
