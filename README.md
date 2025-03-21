# YouTube Comments Sentiment Analysis

This repository contains a Python script (`sentiment_analysis.py`) for performing sentiment analysis on YouTube comments. The script uses Natural Language Processing (NLP) techniques to classify comments as "positive," "negative," or "neutral" based on a provided dataset (`YoutubeCommentsDataSet.csv`). 

## Features
- **Preprocessing**: Cleans text by removing punctuation, converting to lowercase, and filtering out stopwords.
- **Model**: Utilizes TF-IDF vectorization and Logistic Regression from `scikit-learn` to train a sentiment classifier.
- **Interactive Prediction**: Includes a command-line interface to input new comments and predict their sentiment.
- **Evaluation**: Provides accuracy and a detailed classification report for model performance.

## Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `nltk` (install via `pip install pandas numpy scikit-learn nltk`)

## Usage
1. Place your `YoutubeCommentsDataSet.csv` file in the same directory as `sentiment_analysis.py`.
2. Run the script: `python Youtube Comment sentiment analysis.py `.
3. Follow the prompts to test the model with sample comments or enter your own for prediction.

## Dataset
The script expects a CSV file with two columns: "Comment" (text) and "Sentiment" (labels: positive, negative, neutral). Ensure your dataset matches this format.

## Notes
- Handles missing (`NaN`) values in comments gracefully.
- Adjustable parameters like `max_features` in TF-IDF can be tuned for performance.

Contributions and feedback are welcome!
