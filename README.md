# Twitter-X-Social-Media-Sentiment-Analysiss

# Twitter (X) Social Media Sentiment Analysis

## Introduction
This project performs real-time sentiment analysis on Twitter (X) data using Natural Language Processing (NLP). Tweets are collected through the Twitter (X) API using Tweepy and analyzed to classify sentiments as Positive, Negative, or Neutral. The project also includes data visualization techniques such as word clouds, sentiment distribution charts, and network graphs to better understand public opinion and social media trends.

---

## Technologies Used
- Python
- Pandas
- NLTK
- Tweepy
- TextBlob
- Matplotlib
- Seaborn
- NetworkX
- WordCloud
- Twitter (X) API
- Natural Language Processing (NLP)

---

## Features
- Real-time tweet collection using Twitter (X) API
- OAuth 2.0 authentication with Tweepy
- Tweet preprocessing and text cleaning
- NLP-based sentiment classification
- Word cloud generation
- Sentiment trend visualization
- Mention network graph analysis

---

## Installation Method

### Clone the Repository
```bash
git clone https://github.com/your-username/twitter-x-sentiment-analysis.git
cd twitter-x-sentiment-analysis
```

### Install Required Libraries
```bash
pip install tweepy pandas nltk matplotlib seaborn networkx textblob wordcloud
```

### Download NLTK Resources
```bash
python -m nltk.downloader stopwords
python -m nltk.downloader punkt
```

---

## Additional Requirements

### Twitter (X) Developer Account
You will need to create a Twitter (X) Developer Account and generate OAuth 2.0 Bearer Tokens to access the Twitter API.

### Steps to Obtain API Credentials
1. Create a Twitter (X) Developer Account
2. Create a Project and App
3. Generate OAuth 2.0 Bearer Token
4. Replace the token in the code:

```python
BEARER_TOKEN = "YOUR_BEARER_TOKEN"
```

The API credentials are used only for collecting publicly available tweet data for educational and research purposes.

---

## Methodology
1. Collect tweets using Twitter (X) API and Tweepy
2. Preprocess tweet text using NLP techniques
3. Remove stopwords, hashtags, URLs, and special characters
4. Perform sentiment analysis using TextBlob
5. Classify tweets into Positive, Negative, and Neutral categories
6. Generate visualizations and network graphs for insights

---

## Visualizations
- Word Cloud
- Sentiment Distribution Graph
- Tweet Trend Analysis
- Mention Network Graph

---

## Caveats
- Twitter API rate limits may restrict the number of tweets collected
- Sentiment analysis accuracy depends on text quality and slang usage
- Neutral sentiments may sometimes be misclassified
- Real-time results may vary based on trending topics and tweet availability

---

## Future Improvements
- Deep Learning based sentiment analysis
- Real-time dashboard integration
- Multi-language sentiment detection
- Deployment using Streamlit or Flask

---

## Author
Shweta Vishwakarma
