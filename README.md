# 🎮 Game Review Intelligence

An NLP-based system for analyzing video game reviews using classical Machine Learning and DistilBERT.

## 📌 Project Overview

This project analyzes reviews from **2,000 video games** and provides:

- Sentiment classification
- Positive, neutral, and negative review analysis
- Aspect frequency and aspect sentiment
- Automatic key phrase extraction
- Advantages and disadvantages
- Key review points
- Game-to-game comparison
- Interactive Gradio dashboard

## 📊 Dataset

- Games: **2,000**
- Reviews: **100,027 processed reviews**
- Original scraped reviews: **101,862**

The raw dataset is available on Google Drive:

👉 [Download Raw Dataset](https://drive.google.com/file/d/19dgBjbdSuQQImXy6ePW9v0Z895MfM60b/view?usp=drive_link)

> The complete raw dataset is stored externally because of its file size.

## 🤖 Models

The project compares:

- Balanced Logistic Regression
- Balanced Linear SVM
- DistilBERT

The final sentiment model is **DistilBERT**, with threshold optimization for improved minority-class detection.

## 🔍 Review Intelligence

The system extracts:

- 🎯 Sentiment distribution
- 🎮 Game aspects
- 🔑 Key phrases
- 👍 Advantages
- 👎 Disadvantages
- 💡 Key review points
- ⚖️ Game comparisons

## 🖥️ Interactive Dashboard

A colourful **Gradio-based Game Review Intelligence dashboard** allows users to select a game and explore its review insights interactively.

## 📁 Project Structure

```text
game-review-intelligence/
│
├── notebooks/
├── data/
├── README.md
└── requirements.txt
````
🛠️ Technologies

Python
Pandas
NumPy
Scikit-learn
Transformers
DistilBERT
YAKE
Plotly
Gradio
Google Colab

👨‍💻 Project

Game Review Intelligence: An NLP-Based System for Sentiment, Aspect, and Review Analysis
