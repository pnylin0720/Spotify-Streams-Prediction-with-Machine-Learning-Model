# Spotify Streams Prediction with Machine Learning Models

This project uses machine learning to predict Spotify song streaming success based on audio features, song attributes, and artist popularity metrics. The goal is to help the music industry make data-driven decisions for revenue forecasting and risk reduction.

**Team Members:** May Al Khalifa, Jonathan Joseph, Penny Lin, Crystal Wu

### Problem Statement

The music industry faces difficulty in forecasting song success. With the industry becoming increasingly data-driven, it's critical to understand the impact of musical characteristics, artist popularity, exposure, and industry recognition on streaming performance.

### Dataset

- **Source:** [Spotify Top Songs and Audio Features (Kaggle)](https://www.kaggle.com/datasets/julianoorlandi/spotify-top-songs-and-audio-features)
- **Size:** 6,513 unique songs
- **Files:**
  - `spotify_top_songs_audio_features.csv` — Raw dataset from Kaggle  
  - `final_spotify.csv` — Final dataset after preprocessing and feature engineering

### Models Evaluated

We tested 10 different machine learning models:
1. Baseline Model (Mean predictor)  
2. Linear Regression with Cross-Validation  
3. Ridge Regression  
4. Lasso Regression  
5. Elastic Net  
6. K-Nearest Neighbors  
7. Decision Tree & Decision Tree with Pruning  
8. Random Forest  
9. AdaBoost  
10. Gradient Boosting  

### File Structure
- `Dataset/` - Raw dataset and final clean dataset
- `Spotify_Streams_Prediction_Data_Processing.ipynb` - Data preprocessing notebook
- `Spotify_Streams_Prediction_Models.ipynb` - Machine Learning Models with training and evaluation
- `Spotify Streams Prediction Presentation.pdf` - Project Presentation

