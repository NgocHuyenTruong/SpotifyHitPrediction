# Spotify Hit Prediction - Data Science Project  

## Project Overview
This project uses the **Spotify Hit Predictor dataset (1960–2019)** to predict whether a song is likely to be a 'Hit' or a 'Flop.' The dataset consists of various audio features such as danceability, energy, loudness, and more, extracted using Spotify's Web API. Each track is labeled as 'Hit' (1) or 'Flop' (0) based on defined criteria.

## Dataset
The dataset combines features from two files to create a comprehensive collection for analysis and model training. It includes the following attributes:
- **Track Information**: Title, artist, URI.
- **Audio Features**: Danceability, energy, loudness, speechiness, acousticness, instrumentalness, valence.
- **Other Metrics**: Duration (ms), chorus hit, and target.

### Data Source
The dataset is available on [Kaggle](https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset).

## Problem Approach
The problem is a **classic supervised binary classification task**, where the objective is to predict whether a song is a 'Hit' (1) or a 'Flop' (0).

### Steps:
1. **Data Inspection**
   - Import libraries and dataset.
   - Explore and visualize the data.

2. **Data Cleaning and Transformation**
   - Handle missing values and outliers.
   - Scale features for model compatibility.

3. **Model Building and Testing**
   - Train various machine learning models: Logistic Regression, Random Forest, SVM, KNN, and more.
   - Evaluate using metrics like accuracy, precision, recall, and AUC-ROC.

4. **Model Optimization**
   - Analyze the two best models: Random Forest and SVM.
   - Adjust model parameters and thresholds for improved performance.

5. **Prediction**
   - Test the final model with synthetic data for additional validation.

## Results
- The **Random Forest Classifier** was selected as the best model, achieving an accuracy score of approximately **83%**.
- The project demonstrates the iterative nature of machine learning, focusing on continuous model improvement and experimentation.

## Conclusion
This project provides an end-to-end pipeline for predicting song success using machine learning. It illustrates the process of data preparation, model evaluation, and optimization for real-world applications.

## Acknowledgments
I would like to acknowledge the collaborative efforts of my team members, Ngoc Anh Nguyen, Sharanya Prabhu and Thanh Dung Nguyen, in completing this project.
Your teamwork and dedication were invaluable in making this project a success!
