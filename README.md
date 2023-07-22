# MusicClassification

  This repository contains code and data for the Music Genre Classification project as part of the [ShAI Music Genre Classification Challenge](www.kaggle.com/competitions/shai-music-genre-classification-2/data).

## Overview

Music Genre Classification is a task of predicting the genre of a given music track based on its audio features. The dataset provided for this challenge contains almost 14,000 tracks with various audio features and their corresponding genre labels. The goal of this project is to build machine learning models that accurately classify music tracks into different genres.

## Dataset

The dataset for this project contains the following features:

- Artist: Name of the Artist.
- Song: Name of the Track.
- Popularity: Popularity of the song.
- Danceability: A measure of how suitable a track is for dancing.
- Energy: A measure of intensity and activity.
- Key: The key of the track.
- Loudness: Loudness of a track in decibels (dB).
- Mode: Mode (major or minor) of a track.
- Speechiness: Presence of spoken words in a track.
- Acousticness: A confidence measure of the track being acoustic.
- Instrumentalness: Predicts whether a track contains no vocals.
- Liveness: Higher liveness values represent an increased probability that the track was performed live.
- Valence: Describing the musical positiveness.
- Tempo: The speed or pace of a given piece and derives directly from the average beat duration.
- Duration in milliseconds: Time of the song in milliseconds.
- Time_signature: Number of beats (pulses).

#### The target variable is the "Class," representing the Genre of the track.

## Code

music_genre_classification.ipynb: This Jupyter Notebook contains the code for data preprocessing, feature engineering, model training, evaluation, and prediction.

## Models
We explore several machine learning models for music genre classification, including:

- Random Forest Classifier
- Support Vector Machine (SVM) Classifier
- K-Nearest Neighbors (KNN) Classifier
- XGBoost Classifier
- CatBoost Classifier

## Evaluation

We use the weighted F1 score as the evaluation metric for our models. The F1 score takes both precision and recall into account and provides a balanced measure for multi-class classification problems.

We hope this repository helps you explore and experiment with music genre classification using machine learning techniques. 

Happy coding! 🎵🎧
