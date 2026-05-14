# 🧠 AI Text Summarization Web App

A simple AI-powered web application that summarizes long paragraphs into short, meaningful summaries using Natural Language Processing (NLP) and Transformer models.

---

## 🚀 Features

- ✨ AI-based abstractive text summarization
- 📝 Paste long paragraphs and get short summaries
- 🔁 Retains original input after summarization
- ⚡ Fast inference using Hugging Face Transformers
- 🌐 Simple Flask web interface
- 🎨 Clean and responsive UI

---

## 🛠️ Tech Stack

- Python 🐍
- Flask 🌐
- Hugging Face Transformers 🤗
- PyTorch 🔥
- HTML / CSS

---

## 🤖 AI Model Used

This project uses:

facebook/bart-large-cnn


Why this model?
- High-quality abstractive summarization
- Widely used in research and industry
- Balanced accuracy and performance



---

## 📌 How It Works
User pastes a long paragraph
Flask sends text to NLP model
Transformer model generates summary
Summary is displayed on UI
Original text is retained in textarea

## 📦 Requirements
flask
transformers
torch
sentencepiece
