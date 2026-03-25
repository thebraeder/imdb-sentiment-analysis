# IMDB Sentiment Analysis

A machine learning project for classifying IMDB movie reviews as **positive** or **negative** using natural language processing techniques.

## About the Project

This project explores sentiment analysis on a dataset of IMDB movie reviews.  
The task is formulated as a binary text classification problem, where the model predicts whether a review expresses a positive or negative opinion.

## Project Goal

The main goal is to build an effective baseline machine learning model for sentiment classification based on review text.

## Dataset

The dataset consists of:
- Text reviews from IMDB
- Sentiment labels for each review
- Two target classes: positive and negative

## Methodology

The workflow of the project includes:
- Loading and exploring the data
- Cleaning and preparing text data
- Converting text into numerical features with TF-IDF
- Training classification models
- Evaluating model quality on the test set

## Model Performance

The final model achieved an accuracy of 0.89 on the test dataset, demonstrating solid performance in sentiment prediction.

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Files

- `IMDB_model.ipynb` — complete notebook with all project steps
- `README.md` — project documentation

## Final Notes

The results demonstrate that traditional NLP preprocessing and classical machine learning algorithms can serve as an effective solution for text sentiment analysis.
