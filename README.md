# 🎯 Task 4 - Sentiment Analysis using NLP
## CodTech IT Solutions — Data Analytics Internship

![Python](https://img.shields.io/badge/Python-3.14.5%2B-blue)
![NLP](https://img.shields.io/badge/NLP-NLTK%20%7C%20VADER-green)
![ML](https://img.shields.io/badge/ML-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## Internship Details
| Field | Details |
|-------|---------|
| **Name** | Ankit Kumar Pradhan |
| **Intern ID** | CITS442 |
| **Company** | Codtech IT Solutions Private Limited |
| **Domain** | Data Analytics |
| **Mentor** | Neela Santhosh Kumar |
| **Duration** | 4 Weeks |
| **Task** | Sentiment Analysis |

---

## 📌 Objective
Perform **Sentiment Analysis** on textual data (reviews/tweets) using **Natural Language Processing (NLP)** techniques, including both lexicon-based and machine learning approaches.

---

## 📁 Project Structure

```
sentiment-analysis/
│
├── sentiment_analysis.ipynb   # Main Jupyter Notebook (all code here)
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation (this file)
│
└── outputs/                   # Auto-generated when notebook runs
    ├── eda_distribution.png
    ├── wordclouds.png
    ├── confusion_matrices.png
    └── model_comparison.png
```

---

## 🔧 Tech Stack & Libraries

| Category | Libraries |
|----------|-----------|
| Data Handling | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn`, `wordcloud` |
| NLP | `nltk` (tokenization, stopwords, lemmatization, VADER) |
| Machine Learning | `scikit-learn` (TF-IDF, Logistic Regression, Naive Bayes, SVM) |

---

## 🚀 How to Run

### Step 1 — Clone or Download this Repository
```bash
git clone https://github.com/YOUR_USERNAME/codtech-task4-sentiment-analysis.git
cd codtech-task4-sentiment-analysis
```

### Step 2 — Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 3 — Open and Run the Notebook
```bash
jupyter notebook sentiment_analysis.ipynb
```
Then click **"Run All Cells"** from the Kernel menu.

---

## 📊 What the Notebook Covers

| Step | Description |
|------|-------------|
| ✅ 1 | Import all required libraries |
| ✅ 2 | Load dataset (reviews & tweet-style text) |
| ✅ 3 | Exploratory Data Analysis (EDA) |
| ✅ 4 | Data Preprocessing (cleaning, tokenizing, lemmatizing) |
| ✅ 5 | Word Cloud visualization per sentiment class |
| ✅ 6 | VADER Lexicon-based Sentiment Analysis |
| ✅ 7 | ML Models — Logistic Regression, Naive Bayes, SVM |
| ✅ 8 | Model evaluation with confusion matrices |
| ✅ 9 | Predict sentiment on custom new text |
| ✅ 10 | Key insights and findings |

---

## 🤖 Models Used

### 1. VADER (Valence Aware Dictionary and sEntiment Reasoner)
- Rule-based / Lexicon approach
- Works directly on raw text
- Great for social media / short texts

### 2. Machine Learning Models (with TF-IDF features)
- **Logistic Regression** — strong baseline classifier
- **Naive Bayes** — fast and effective for text
- **Linear SVM** — powerful for high-dimensional text data

---

## 📈 Key Insights

- **Preprocessing** (stopword removal, lemmatization) significantly improves model performance
- **Positive reviews** tend to be longer and contain words like *amazing, excellent, love*
- **Negative reviews** use stronger emotional words like *terrible, worst, disappointed*
- **Logistic Regression** achieved the best accuracy among ML models
- **VADER** performs well without any training — good for quick sentiment checks

---

## 🧪 Sample Predictions

```
Text     : "I really enjoyed the internship experience at CodTech!"
ML Model : 😊 Positive
VADER    : Positive

Text     : "The task was too difficult and instructions were unclear."
ML Model : 😠 Negative
VADER    : Negative
```

---

## 📦 Requirements

See `requirements.txt` for full list. Main packages:
```
pandas, numpy, matplotlib, seaborn
nltk, wordcloud
scikit-learn
jupyter
```

---

## 👤 Intern Details

- **Internship Company:** CodTech IT Solutions Private Limited  
- **Domain:** Data Analytics  
- **Task:** Task 4 — Sentiment Analysis  
- **Duration:** 4 Weeks (Virtual Internship)

---

*Submitted as part of CodTech IT Solutions Data Analytics Internship — Task 4*
