# Semantic_Analysis_Streamlit


This Streamlit app facilitates sentiment analysis on text inputs provided by users, both through direct input and file uploads. It leverages the TextBlob library for sentiment analysis and cleantext library for text preprocessing.

# Sentiment Analysis on User Input:

Users can input text directly into the provided text box.
Upon submission, the app calculates the sentiment polarity and subjectivity of the entered text using TextBlob.
The sentiment polarity represents the sentiment score ranging from -1 (negative) to 1 (positive), while subjectivity indicates the extent of the text being subjective or opinionated.
Text Preprocessing:

Users can also preprocess text before sentiment analysis using options provided.
The preprocessing options include cleaning text by removing non-alphanumeric characters, extra spaces, stopwords, converting text to lowercase, removing numbers, and punctuation.
Sentiment Analysis on Uploaded CSV:

Users can upload a CSV file containing text data for sentiment analysis.
The app reads the uploaded CSV file and performs sentiment analysis on the specified column (assumed to be named 'tweets').
It calculates sentiment scores for each text entry and categorizes them into positive, negative, or neutral based on defined thresholds.
The analyzed data is displayed as a DataFrame, showing the original text, sentiment score, and sentiment analysis result.
Data Export:

Users can download the analyzed data as a CSV file for further analysis or reference.

# Usage:

To utilize the app, users can input text directly or upload a CSV file containing text data.
They can choose preprocessing options to clean the text if needed.
After analysis, users can view sentiment analysis results directly on the app interface and download the analyzed data for offline use or further processing.
Dependencies:

The app relies on Streamlit, TextBlob, Pandas, and cleantext libraries. Make sure to install these dependencies before running the app.

# Note:

Ensure that the CSV file uploaded contains a column named 'tweets' for sentiment analysis.
The app provides an easy-to-use interface for conducting sentiment analysis tasks on text data.
