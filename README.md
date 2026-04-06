# Netflix Content-Based Recommendation System

## Overview
This repository contains a Jupyter Notebook developed in Google Colab that implements a content-based recommendation system for Netflix titles (movies and TV shows). The system recommends similar content based on two main criteria: shared genres and semantic similarity of descriptions using TF-IDF.

## Features
- **Data Loading and Preprocessing**: Handles missing values and prepares the dataset for analysis.
- **Genre-Based Similarity**: Calculates content similarity based on shared genres using Cosine Similarity.
- **Description-Based Similarity**: Utilizes TF-IDF vectorization on content descriptions to find semantically similar titles.
- **Interactive Recommendation Function**: A Python function to get top N recommendations for any given title.
- **Data Visualization**: Includes visualizations such as genre distribution and movie duration by rating using violin plots.

## Technologies Used
- Python 3
- Pandas
- Scikit-learn (for TF-IDF and Cosine Similarity)
- Matplotlib
- Seaborn
