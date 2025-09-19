# 🐦 Twitter Sentiment Analysis

This project analyzes social media (Twitter) posts and predicts sentiment as **Positive, Negative, or Neutral** using **NLP + Machine Learning**.

---

## 📌 Features
- Data preprocessing (cleaning tweets, removing emojis, stopwords, links, mentions)
- NLP techniques (tokenization, lemmatization, wordclouds)
- Sentiment classification using Logistic Regression
- Visualization: Pie charts, word frequencies, and word clouds
- Public Opinion Style Report in HTML

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- NLTK / TextBlob
- WordCloud
- Jupyter Notebook

---

## 📂 Project Structure
├── TwitterSentimentAnalysis.ipynb # Main notebook
├── TwitterSentimentAnalysis.html # Exported HTML report
├── Tweets.csv # Dataset (optional)
├── sentiment_logreg_model.joblib # Trained ML model
├── tfidf_vectorizer.joblib # TF-IDF vectorizer
└── README.md # Project documentation

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/Twitter-Sentiment-Analysis.git
2. Install dependencies:
pip install -r requirements.txt
3. Open Jupyter Notebook:
jupyter notebook TwitterSentimentAnalysis.ipynb


📊 Results
Most tweets are negative (airlines dataset case).
Wordcloud shows "delay", "cancelled", "bad service" in negative tweets.
Positive tweets include words like "great", "thanks", "love".



🌐 Live Report
👉 Click here to view HTML Report:
https://fatima-eman-hub.github.io/Twitter-Sentiment-Analysis/
