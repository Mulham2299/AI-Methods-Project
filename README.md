# 🛍️ Sentiment Analysis Pipeline – Amazon Reviews (Logistic Regression, Naive Bayes, CNN)

This project was developed during my studies at Northumbria University. It explores how traditional and deep learning models perform on large-scale sentiment classification tasks using real-world Amazon review data.

---

## 🎯 Project Goals

- Compare the performance of Logistic Regression, Naive Bayes, and CNN models
- Understand trade-offs between accuracy, efficiency, and interpretability
- Build a scalable NLP pipeline with ethical AI considerations

---

## 🧪 Pipeline Overview

### 🔄 Preprocessing
- Tokenization, lemmatization, and stop word filtering using **NLTK**
- TF-IDF vectorization for traditional models
- Sequence padding for CNN input

### 🧠 Modeling
- **Binary classification**: Positive vs. Negative sentiment
- Models used:
  - Logistic Regression
  - Naive Bayes
  - Convolutional Neural Network (CNN)

### 📊 Evaluation
- Metrics: Accuracy, Precision, Recall, F1-score
- Confusion matrix visualizations
- Runtime analysis for model efficiency

---

## 📈 Key Results

| Model              | Accuracy | Precision | Recall | F1-Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 87%      | —         | —      | 0.87     |
| CNN                | —        | 0.87      | 0.86   | 0.86     |
| Naive Bayes        | 83%      | —         | —      | —        |

---

## 🛠️ Tech Stack

| Tool / Library     | Purpose                          |
|--------------------|----------------------------------|
| Python 3.x         | Core programming language        |
| NLTK               | Text preprocessing               |
| scikit-learn       | Traditional ML models & TF-IDF   |
| TensorFlow / Keras | CNN implementation               |
| matplotlib / seaborn | Visualization of metrics        |

---
