# 📰 News Summarization & Sentiment Analysis (Hindi TTS)

This project fetches news articles about a given company, summarizes them, analyzes their sentiment, translates the summaries to Hindi, and generates Hindi audio using Google Text-to-Speech.

## ✨ Features

- 🔍 Fetch news from **NewsAPI** based on a company name
- 🧠 Summarize and perform **sentiment analysis** (Positive/Negative/Neutral)
- 🌐 Translate summaries from **English to Hindi**
- 🔊 Convert Hindi text summaries to **audio (mp3)**
- 📊 Generate **comparative analysis** of article sentiment
- 🖥️ **Streamlit UI** and **Flask API** for interaction

---

## 🏗️ Project Structure

```bash
news-sentiment-analysis/
│
├── api.py               # Flask backend for processing and analysis
├── app.py               # Streamlit frontend interface
├── utils.py             # Helper functions (summarization, sentiment, TTS, etc.)
├── requirements.txt     # List of dependencies
├── .gitignore           # Files to ignore in Git
└── README.md            # This file
