# SENTIMENT-ANALYSIS
#✈️ Twitter US Airline Sentiment Analysis – NLP Project
Project Title: Sales Navigator Dashboard
Company: Codtech IT Solutions
Name: Radhika
Intern ID: CT04DF1997
Domain: Data Analytics
Duration: 4 Weeks
Mentor: Neela Santosh

This project is part of Task 4 of my Data Analyst Internship at CODTECH IT SOLUTIONS, focused on performing Sentiment Analysis using Natural Language Processing (NLP) techniques on real-world text data. The dataset used contains thousands of tweets directed at major U.S. airlines and is labeled with sentiments: positive, negative, or neutral. The objective of this project was to process and analyze these tweets to uncover patterns and train a machine learning model that accurately predicts sentiment from raw text.

The dataset, titled Twitter US Airline Sentiment, is sourced from Kaggle and includes over 14,000 tweets. Each tweet is associated with the name of the airline and a sentiment label indicating the tone of the message. The project began with data exploration and cleaning. This involved identifying missing values, checking data types, and understanding the distribution of sentiment labels across different airlines. The distribution showed that the majority of tweets were negative, followed by neutral and then positive sentiments.

The next major step was applying NLP preprocessing techniques. Using Python libraries like nltk and re, I removed URLs, mentions, special characters, and numbers. All text was converted to lowercase to maintain uniformity. Then, I performed tokenization, stopword removal, and lemmatization to simplify the text while preserving its meaning. This made the data more suitable for training the machine learning model.

To convert the cleaned text into a format understandable by machine learning algorithms, I used TF-IDF vectorization. TF-IDF (Term Frequency–Inverse Document Frequency) transforms textual data into numerical values by evaluating how important each word is to a document relative to the entire dataset.

For classification, I chose Logistic Regression, a widely used algorithm for text classification tasks. The dataset was split into training and testing sets using train_test_split, and the model was trained on the TF-IDF features. Once the model was trained, its performance was evaluated using accuracy, precision, recall, and F1-score. The results showed that the model could effectively predict the sentiment of tweets, especially negative ones, which had the largest sample size.

In addition to modeling, I created a range of visualizations using matplotlib, seaborn, and wordcloud. These included:

- A pie chart of sentiment distribution

- Bar plots showing sentiment counts by airline

- Box plots displaying sentiment confidence scores

- Word clouds for each sentiment category

- Bar charts of the most frequent words per sentiment class

These visualizations provided clear insights into user behavior and sentiment trends. For instance, most complaints were related to United Airlines, and positive feedback often centered around timely service and helpful staff.

This project demonstrates how powerful and insightful NLP can be when combined with machine learning and proper visualization. It covers a complete sentiment analysis pipeline: from raw data collection to preprocessing, feature extraction, model building, evaluation, and insight generation.
