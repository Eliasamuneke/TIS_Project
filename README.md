# Sentiment Analysis on Twitter Tweets

## Overview

This repository contains the code for a sentiment analysis project focused on classifying sentiments in Twitter tweets. The project aims to train a performant model using the Twitter Tweets Sentiment classification dataset. Participants can engage in a leaderboard competition to achieve the highest model performance.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- transformers: `pip install transformers`
- torch: `pip install torch`
- pandas: `pip install pandas`

### Setup

1. Clone this repository:

2. Download the dataset:

   Ensure that the "archive" folder, containing the "Tweets.csv" dataset, is included in the repository. You can download the dataset from [here](https://www.kaggle.com/datasets/yasserh/twitter-tweets-sentiment-dataset).

3. Open and run the Jupyter Notebook:

    ```bash
    jupyter notebook CS410_tweet_classifier_model.ipynb
    ```

    This notebook contains the code for training and evaluating the sentiment analysis model. Make necessary edits to hyperparameters and model architecture as needed.

## Running the Code

- Execute the notebook cell by cell to train and evaluate the sentiment analysis model. Ensure that the required dependencies are installed.
## Results

After fine-tuning the model, the evaluation on the testing set yielded the following results:

- Accuracy: 71.62%
- Classification Report:

            precision    recall  f1-score   support

       0       0.80      0.61      0.69      1562
       1       0.86      0.64      0.73      1705
       2       0.62      0.85      0.72      2230

accuracy                           0.72      5497


macro avg 0.76 0.70 0.72 5497
weighted avg 0.75 0.72 0.72 5497

## Issues and Challenges

If you encounter any issues or face challenges, please refer to the Issues section or create a new issue.

## Acknowledgments

This project was developed as part of CS 410: Text Information Systems at illinois.

## License

This project is licensed under the [MIT License](LICENSE).
