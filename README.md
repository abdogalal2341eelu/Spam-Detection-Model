# 📩 Spam Detection using Random Forest & CountVectorizer

This project is a machine learning model that classifies emails as either **Spam** or **Ham (Not Spam)** using a Random Forest classifier. The dataset contains over 190,000 emails and the model achieves high accuracy after preprocessing and training.

---

## 📁 Dataset

- **Source:** [Kaggle – 190K Spam/Ham Email Dataset](https://www.kaggle.com/datasets/meruvulikith/190k-spam-ham-email-dataset-for-classification/data)
- **Size:** ~190,000 labeled emails
- **Classes:** `Spam`, `Ham`

---

## 🧠 Model Overview

| Component          | Description                            |
|-------------------|----------------------------------------|
| Model             | `RandomForestClassifier`               |
| Features          | `CountVectorizer`                      |
| Preprocessing     | Lowercasing, Punctuation Removal, Tokenization, Stopwords Removal, Stemming |
| Language Tools    | NLTK (stopwords + stemmer)             |

---

## ⚙️ How it Works

1. **Load and Clean Data**
2. **Preprocess Text** using NLP techniques
3. **Convert to Features** using `CountVectorizer`
4. **Split** data into train/test sets
5. **Train Model** with Random Forest
6. **Evaluate** using metrics
7. **Export Model** and `vectorizer` with `joblib` / `pickle`
8. **Predict** new messages

---

## 📊 Model Performance

| Metric     | Score     |
|------------|-----------|
| Accuracy   | 98.1%     |
| Precision  | 98.1%     |
| Recall     | 98.1%     |
| F1 Score   | 98.1%     |

📌 **Confusion Matrix:**

