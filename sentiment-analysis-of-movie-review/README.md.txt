# Sentiment Analysis of IMDb Top 1000 Movies and TV Shows

This project performs **sentiment analysis** on the **IMDb Top 1000 Movies and TV Shows** dataset using Natural Language Processing (NLP) techniques. The objective is to determine whether the overview (description) of each movie or TV show expresses a positive or negative sentiment.

## Project Overview

The project involves the following steps:

1. **Data Loading**: We load the IMDb dataset containing information on the top 1000 movies and TV shows.
2. **Data Preprocessing**: We clean the text data by removing special characters, punctuation, and stop words.
3. **Sentiment Analysis**: Using the TextBlob library, we classify each movie or TV show's description as having either a positive or negative sentiment.
4. **Visualization**: We visualize the distribution of positive and negative sentiments across the dataset.

## Dataset

The dataset used in this project is available on Kaggle: [IMDb Dataset of Top 1000 Movies and TV Shows](https://www.kaggle.com/datasets/stefanoleone992/imdb-extensive-dataset).

### Dataset Columns

- `Title`: Name of the movie or TV show.
- `Overview`: Brief description of the movie or TV show.
- `Genre`: The genre of the movie or show (e.g., Drama, Action, Comedy).
- `Rating`: IMDb rating.

## Project Files

- `notebook.ipynb`: The main notebook containing the code for loading data, preprocessing, sentiment analysis, and visualization.
- `README.md`: This file that provides an overview and instructions for the project.

## How to Run the Project

1. Clone this repository or download the notebook.
2. Load the notebook on Kaggle or a local Jupyter environment.
3. Install the necessary dependencies (all dependencies are available on Kaggle).
4. Run all cells in the notebook sequentially to complete the sentiment analysis.

## Installation

You can install the required libraries by running:

```bash
pip install pandas numpy nltk textblob matplotlib
