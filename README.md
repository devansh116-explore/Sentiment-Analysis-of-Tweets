# 🐦 Sentiment Analysis for Tweets

This project performs **sentiment analysis** on tweets using machine learning, specifically **Logistic Regression**. It classifies tweets as either **positive** or **negative** based on their content.

---

## 📁 Files

- `Sentiment Analysis for Tweets.ipynb` – Jupyter Notebook with full implementation
- `trained_model.sav` – Saved Logistic Regression model
- `kaggle.json` – Your Kaggle API token (required to download the dataset)

---

## 📊 Dataset

- **Source**: [Sentiment140 - Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)
- The dataset contains 1.6 million tweets labeled as positive or negative.

---

## 🔧 Project Workflow

### 1. **Setup & Dataset Download**
- Install `kaggle` library
- Upload your `kaggle.json` to access the API
- Download the dataset using:
  ```bash
  kaggle datasets download -d kazanova/sentiment140
