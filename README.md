# Movie Recommendation Predictor using KNN

A KNN-based machine learning project, designed to predict a movie's commercial success by analyzing TMDB data. We use cosine similarity for feature comparison and TF-IDF for text vectorization.

## Dataset and Preprocessing

The project uses two datasets: `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`. Data is merged on movie IDs to create a unified dataset including:
- Genres
- Keywords
- Top 3 cast members
- Director
- Movie overview

## Feature Engineering

- JSON columns converted to lists.
- Text data combined into a 'tags' column, serving as the basis for similarity comparison.
- TF-IDF vectorization of the 'tags' column to transform text data into feature vectors.

## Recommendation System

The KNN model is implemented using cosine similarity to measure the distance between movies' feature vectors.

## Example Usage

```python
recommend('Inception', similarity_matrix, joined_df)



For questions or contributions, please contact spomar36@gmail.com.

Cloud Production Services and ML Operations
AWS: Store datasets and manage ML models with Amazon S3 and SageMaker.

Azure: Use Blob Storage for data and Azure Machine Learning for model operations.

GCP: Leverage Google Cloud Storage and AI Platform for end-to-end ML workflows.


ML Operations
Continuous Learning: Models are retrained with updated data for accuracy.
Data Validation: Regular checks for data quality and integrity.
Model Monitoring: Ongoing performance tracking to detect and address data drift.


Setup and Run
git clone https://github.com/GOSS-hash/k-nearest-neighbors-project-tutorial-omass/tree/main
