# Twitter Sentiment Analysis

This project performs sentiment analysis on Twitter data to determine the sentiment (positive, negative, or neutral) of tweets. It uses machine learning techniques to classify the sentiment of each tweet based on its content.

## Overview

The Twitter Sentiment Analysis project aims to analyze the sentiment expressed in tweets. It employs natural language processing and machine learning algorithms to classify the sentiment of each tweet as either positive, negative, or neutral. The project utilizes a labeled dataset of tweets for training and evaluation purposes.

## Features

- Preprocessing of raw tweets: The tweets are preprocessed to remove special characters, digits, and stopwords, and to perform lemmatization.
- Feature extraction: Textual features are extracted from the preprocessed tweets, such as word frequency, n-grams, or word embeddings.
- Model training: Various machine learning algorithms are employed to train a sentiment classification model using the labeled dataset.
- Sentiment prediction: The trained model is used to predict the sentiment of new, unseen tweets.
- Evaluation: The accuracy, precision, recall, and F1-score of the sentiment classification model are computed using evaluation metrics such as confusion matrix and classification report.

## Individual Tasks

This project involves the following individual tasks performed by team members:

1. **Data Collection (Performed by Kinde):** Kinde is responsible for collecting a large dataset of tweets from Twitter using the Twitter API. He retrieves tweets related to specific topics of interest and gathers the necessary data for sentiment analysis. The collected data includes tweets along with their sentiment labels.

2. **Data Preprocessing and Feature Extraction (Performed by  Bruce): Bruce is responsible for preprocessing the raw tweets. He removes special characters, digits, and stopwords from the text, and performs lemmatization to standardize the words including part-of-speech(POS) Tagging. Bruce ensures that the data is cleaned and ready for further processing and analysis.Bruce explores different feature extraction techniques and selects the most suitable ones for the sentiment analysis task.


3. **Model Training (Performed by Kinde):** Kinde is responsible for training the sentiment classification model. She experiments with different machine learning algorithms such as Naive Bayes, Support Vector Machines, or Neural Networks. Kinde tunes the hyperparameters, performs cross-validation, and selects the best-performing model for sentiment classification.

4. **Model Evaluation (Performed by Bruce):** Bruce is responsible for evaluating the performance of the trained sentiment classification model. He computes various evaluation metrics such as accuracy, precision, recall, and F1-score. Bruce analyzes the model's performance on different datasets and identifies areas for improvement.

5. **Web Application Development (Performed by Kinde):** Kinde is responsible for developing the web application that allows users to interact with the sentiment analysis system. He designs the user interface, integrates the trained model into the application, and ensures a smooth user experience. Kinde also handles deployment and maintenance of the web application.

6. **Documentation and Reporting (Performed by Bruce and Kinde):** Bruce is responsible for documenting the project, creating user guides, and preparing technical reports. Kinde keeps track of the project progress, documents the methodologies used, and summarizes the key findings and results. Bruce ensures that the project documentation is up-to-date and easily accessible to the team and stakeholders.

## Installation

1. Clone the repository:



## Installation

1. Clone the repository:


2. Install the required dependencies:


3. Download the pre-trained models or train your own model using the provided dataset.

4. Run the application:



## Usage

1. Access the web application by navigating to http://127.0.0.1:5000 in your web browser.

2. Enter a sentence or tweet in the input field.

3. Click on the "Predict" button to classify the sentiment of the input text.

4. The predicted sentiment (positive, negative, or neutral) will be displayed on the screen.

## Dataset

The project uses a labeled dataset of tweets for training and evaluation. The dataset contains tweets along with their corresponding sentiment labels (positive, negative, or neutral). The dataset is available in the `data` directory of the project.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
