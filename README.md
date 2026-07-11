# 📊 Sentiment Analysis Model for Reviews

A machine learning-powered sentiment analysis application designed to understand, classify, and extract insights from user reviews. This project leverages a classic TF-IDF and Machine Learning pipeline to predict whether a given review is positive, negative, or neutral, and serves it through a user-friendly interface.

---

## 🚀 Features

* **Text Preprocessing:** Vectorizes text inputs using a pre-trained TF-IDF vectorizer.
* **Predictive Modeling:** Utilizes a saved machine learning model (`.pkl`) to accurately classify review sentiments.
* **Web Application:** Features an interactive interface (built with `app.py`) for real-time review testing.
* **Production Ready:** Easily deployable using standard Python environment configurations.

---

## 📁 Repository Structure

* `app.py`: The main application script containing the backend logic and user interface.
* `sentiment_model.pkl`: The trained machine learning model serialization file.
* `tfidf_vectorizer.pkl`: The saved TF-IDF vectorizer used to transform raw text into numerical features.
* `requirements.txt`: List of required Python packages and dependencies for seamless setup.

---

## 🛠️ Installation & Setup

Follow these steps to get the application running locally on your machine.

### 1. Clone the Repository
```bash
git clone [https://github.com/lokesh-analytic/-Sentiment-analysis.git](https://github.com/lokesh-analytic/-Sentiment-analysis.git)
cd -Sentiment-analysis
