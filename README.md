# 📰 Fake News Detection using Machine Learning & NLP

A complete machine-learning pipeline for detecting fake news using NLP techniques, TF-IDF vectorization, and Logistic Regression.  
This project includes data preprocessing, visualization, model training, evaluation, and prediction—all inside a Jupyter Notebook.

---

## 📌 Project Overview

This repository implements an end-to-end workflow for fake news classification.  
The pipeline includes:

- Data loading & cleaning  
- Exploratory data analysis (EDA)  
- Text preprocessing (stopwords, punctuation removal, lemmatization)  
- Feature extraction using **TF-IDF**  
- Training a **Logistic Regression** classifier  
- Evaluation (accuracy, classification report, confusion matrix)  
- Visualization (word clouds, term frequencies, feature weights)  
- A demo function for article predictions  

---

## 🧠 Model Summary

- **Model:** Logistic Regression  
- **Features:** TF-IDF on preprocessed text  
- **Labels:**  
  - `0` → Real news  
  - `1` → Fake news  

The model achieves competitive accuracy and interpretable output through weighted feature inspection.

---

## 🗂 Dataset

Expected dataset files:

| File | Description |
|------|-------------|
| `train.csv` | Training data containing labeled news articles |
| `test.csv` | Test data for evaluating the model |

Columns used:

- `title`
- `text`
- `label` (0 = real, 1 = fake)

---

## 🔧 Text Preprocessing

The NLP pipeline performs:

- Lowercasing  
- Punctuation removal  
- Stopword removal (NLTK)  
- Lemmatization (WordNet)  
- Tokenization  

Feature extraction is done using **TF-IDF vectorizer**.

Visualizations include:

- WordCloud  
- Term frequency histograms  
- Key positive/negative feature bar charts  

---

## 📊 Evaluation

The notebook outputs:

- Accuracy score  
- Confusion matrix  
- Classification report  
- Feature importance visualization  
- Word distribution plots  

---

## 🚀 Running the Project

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
