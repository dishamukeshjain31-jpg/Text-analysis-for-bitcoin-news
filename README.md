# Text-analysis-for-bitcoin-news
Sentiment analysis and topic modelling along with visual representation
Bitcoin News Analysis
📌 Overview

This project analyzes Bitcoin news headlines to understand the overall sentiment, topics, and common word patterns around Bitcoin in the media.

The analysis covers:

Text preprocessing (cleaning, tokenization, stopword removal)

Sentiment analysis using TextBlob

Topic modeling using NMF (Non-negative Matrix Factorization) and TF-IDF

Visualization with Word Clouds, Bar Charts, and Pie Charts

N-gram analysis (bigrams and trigrams)

This project can be extended to track how media sentiment about Bitcoin changes over time.

⚙️ Technologies Used

Python 🐍

Pandas – Data handling

NLTK – Tokenization & stopwords removal

TextBlob – Sentiment analysis

Scikit-learn – TF-IDF & NMF topic modeling

Matplotlib & WordCloud – Data visualization

Excel – Input/output for storing results

📊 Analysis Performed

🔹 Preprocessing

Converted text to lowercase

Removed special characters

Tokenized words

Removed stopwords

🔹 Sentiment Analysis

Classified news headlines into Positive, Negative, Neutral

Pie chart shows sentiment distribution

🔹 Topic Modeling

Extracted 4 main topics from Bitcoin-related headlines

Visualized with bar charts and word clouds

🔹 N-gram Analysis

Identified the most common bigrams (e.g., "bitcoin price")

Identified the most common trigrams (e.g., "bitcoin price today")

Sample Outputs

Sentiment Distribution (Pie Chart)

Top Words per Topic (Bar Charts)

Word Clouds for each topic

Top 20 Bigrams and Trigrams (Table Output)
Future Improvements

Incorporate time series analysis to see how sentiment changes over time

Use advanced models like VADER or transformer-based sentiment analysis (BERT/FinBERT)

Deploy results on a dashboard (Streamlit / Dash)
