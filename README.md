Mama Earth Sentiment Analysis

Welcome to the Mama Earth Sentiment Analysis project! This project aims to analyze customer reviews of Mama Earth products to understand the sentiment behind them. By leveraging both traditional and advanced machine learning techniques, the project provides insights into customer feedback and helps in identifying areas of improvement.
Table of Contents

    Introduction
    Data
    Models
    Results
    Contribution
    License

Introduction

This project uses Natural Language Processing (NLP) techniques to analyze customer reviews for sentiment. The goal is to classify reviews into positive, negative, or neutral sentiments and draw insights from customer feedback to improve the product.
Installation

To set up the project locally, follow these steps:

    Clone the repository:

    bash

git clone https://github.com/TanishqThuse//Sentimental_Analysis.git
cd Mama_Earth_Sentiment_Analysis

Create a virtual environment and activate it:

bash

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Usage

To run the sentiment analysis, follow these steps:

    Open the Jupyter notebook:

    bash

    jupyter notebook Mama_Earth_Sentiment_Analysis.ipynb

    Execute the cells in the notebook to perform data loading, processing, model training, and analysis.


Data

The dataset used in this project consists of customer reviews, which include text reviews and ratings for Mama Earth products. The data is stored in CSV format with columns for review text, ratings, and other relevant information.

To use your own data, place your data files in the data/input/ directory. Ensure that the CSV files have the necessary columns (e.g., review text, ratings).
Models

This project employs two main sentiment analysis tools:

    VADER (Valence Aware Dictionary and sEntiment Reasoner): A lexicon and rule-based sentiment analysis tool that is particularly effective for social media texts.

    RoBERTa (A Robustly Optimized BERT Pretraining Approach): A transformer-based model fine-tuned for sentiment analysis tasks. It provides a more nuanced understanding of sentiment in text data.

The notebook compares the performance of these models and analyzes their predictions.
Results

The analysis provides insights into the sentiment of customer reviews. Key findings include:

    Distribution of positive, negative, and neutral sentiments.
    Examples of reviews with significant discrepancies between star ratings and sentiment scores.
    Visualizations of sentiment scores across different product ratings.

The detailed results and visualizations are available in the Jupyter notebook.
Contribution

Contributions are welcome! If you have suggestions for improvements or have found bugs, please open an issue or submit a pull request. Make sure to follow the repository's code of conduct.
License

This project is licensed under the MIT License - see the LICENSE file for details.
