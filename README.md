# Sentiment Analysis Project

## Overview
This project focuses on sentiment analysis using machine learning techniques. It analyzes the sentiment (positive or negative) of text data, such as tweets, using a Naive Bayes classifier trained on a dataset of labeled text.

## Features
- Data preprocessing: The project preprocesses the text data by removing stopwords, URLs, mentions, and hashtags.
- Word clouds: Visualizes the most frequent words in positive and negative sentiment tweets using word clouds.
- Naive Bayes classifier: Trains a Naive Bayes classifier on the preprocessed text data to classify sentiments as positive or negative.
- Evaluation: Evaluates the classifier's performance on a test dataset, reporting the accuracy for both positive and negative sentiments.

## How to Use
1. **Dependencies**: Make sure you have all the required dependencies installed. You can install them using `pip`:
   ```bash
   pip install numpy pandas scikit-learn nltk wordcloud matplotlib
   ```
2. **Clone the Repository**: Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis.git
   ```
3. **Run the Code**: Navigate to the project directory and run the Python script:
   ```bash
   cd sentiment-analysis
   python sentiment_analysis.py
   ```
4. **View Results**: After running the script, you'll see the evaluation results printed in the console, along with the word clouds visualizations.

## Dataset
The dataset used in this project is a CSV file containing text data labeled with sentiments (positive, negative, neutral). The dataset is available in the `Sentiment.csv` file.

## License
This project is licensed under the [MIT License](LICENSE).



