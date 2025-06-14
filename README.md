# 🎬 Movie Recommender System

This project implements a simple content-based movie recommender system that suggests similar movies based on their genre information. The system utilizes machine learning techniques such as text vectorization and cosine similarity to analyze the genre data and recommend movies that are most similar to a given movie title.

## 📖 Project Description

- **Type:** Content-Based Filtering
- **Language:** Python
- **Libraries:** pandas, scikit-learn
- **Dataset:** Disney Movies Dataset (`disney movies.csv`)

The genres column in the dataset is processed using `CountVectorizer` to create a Bag-of-Words representation. Cosine similarity is then computed on this genre matrix to measure the similarity between movies. Based on a selected movie title, the system recommends other movies with the highest similarity scores.

## 🛠️ Technologies Used

- **pandas** for data manipulation
- **scikit-learn** for vectorization (`CountVectorizer`) and similarity computation (`cosine_similarity`)
- **Jupyter Notebook** for implementation and testing

