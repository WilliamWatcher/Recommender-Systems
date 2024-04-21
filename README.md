# MIND Dataset Recommender System Project

## Overview
This project is an exploration into the creation of news recommender systems using the MIND small dataset. The repository is made in relation to a group assignment in the course TDT4215 - Recommender Systems at NTNU.

## Repository Contents

- **Notebooks:**
  - `evaluation.ipynb` - Contains the evaluation metrics for the recommender systems.
  - `evaluation_logistic_reg.ipynb` - Specific evaluation for the logistic regression model within feature-based recommendation.
  - `feature_based.ipynb` - Implements the feature-based recommendation system.
  - `item_collab_filtering.ipynb` - Implements item-based collaborative filtering approach.
  - `most_popular.ipynb` - Central notebook with an overview and aggregated findings.

- **Directories:**
  - `.vscode` - Contains VSCode settings and configurations.
  - `data` - Expected to hold the MIND dataset files.
  - `venv` - Houses a Python virtual environment (own setup required).
  - 
## Methods Implemented

- **Most Popular**: Establishes a baseline by highlighting recent, frequently clicked articles.
- **Feature Based Recommendation**: 
  - Utilizes TF-IDF for text feature extraction and logistic regression for user interaction predictions.
- **Item-based Collaborative Filtering**: 
  - Applies matrix factorization (ALS) and locality-sensitive hashing (LSH) for recommending articles based on user's past interactions.

## Evaluation Metrics

- **Normalized Distributed Cumulative Gain (nDCG)**: Quantifies the rank quality of clicked articles in the recommendations.
- **Precision at K**: Measures the fraction of relevant articles among the top 'K' recommendations.

## How to Use This Repository

1. Clone the repository to your local machine.
2. Ensure the `data` directory contains the MIND small dataset.
3. Set up a virtual environment and install dependencies.
4. Run the respective Jupyter notebook.
