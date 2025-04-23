# lyrics-sentiment

# Sentiment Analysis on Song Lyrics
This NLP project analyzes the sentiment of song lyrics across various genres using machine learning. It involves web scraping, data cleaning, text preprocessing, sentiment labeling, model training, and visualization.

## Tools & Technologies
- Python  
- BeautifulSoup (Web Scraping)  
- pandas, numpy  
- scikit-learn (Naive Bayes, Logistic Regression)  
- matplotlib, seaborn (Visualization)

## Project Overview
- Collected 500+ lyrics from pop, indie, and rap songs using scraping tools  
- Cleaned and tokenized raw text data  
- Applied ML models to classify lyrics into positive/negative sentiment  
- Visualized sentiment trends by genre using Python plots

## Files
- `lyrics_scraper.py` – Web scraper for song lyrics  
- `cleaning_utils.py` – Cleaning and preprocessing functions  
- `sentiment_model.ipynb` – Model training and evaluation notebook  
- `visualizations.ipynb` – Data plots and insights

## Results
- Logistic regression model reached approximately 82% accuracy  
- Clear genre trends emerged: indie lyrics leaned more negative, while pop skewed positive

## Try it yourself
[Open in Colab](https://colab.research.google.com/github/sh1hlin/lyrics-sentiment/blob/main/sentiment_model.ipynb)

## Link
View full project on GitHub: [https://github.com/sh1hlin/lyrics-sentiment](https://github.com/sh1hlin/lyrics-sentiment)
