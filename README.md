# Fraud Job Detection

A machine learning project that detects fraudulent job postings using natural language processing (NLP) techniques applied to job listing data.

## 📌 Overview

Online job boards are increasingly targeted by scammers posting fake job listings to steal personal information or money from applicants. This project builds a classification model that analyzes job posting text and metadata to predict whether a listing is **genuine** or **fraudulent**.

## 🎯 Problem Statement

Given a dataset of job postings (title, description, requirements, company profile, etc.), classify each posting as:
- `0` — Real job
- `1` — Fraudulent job

## 🗂️ Dataset

- Source: [Add dataset link, e.g. Kaggle "Real or Fake Job Posting Prediction"]
- Features used: job title, description, requirements, company profile, location, employment type, required experience/education, etc.
- Target: `fraudulent` (binary label)

## ⚙️ Tech Stack

- **Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, NLTK / spaCy, matplotlib, seaborn
- **Model(s):** Logistic Regression / Random Forest / XGBoost *(update based on what you used)*
- **NLP techniques:** TF-IDF / CountVectorizer / word embeddings *(update as applicable)*

## 🔍 Approach

1. **Data Cleaning** — Handle missing values, remove HTML tags/special characters from text fields
2. **EDA** — Explore class imbalance, most common words in fraudulent vs. real postings
3. **Feature Engineering** — Text vectorization (TF-IDF), combining text + categorical features
4. **Model Training** — Train and compare multiple classifiers
5. **Evaluation** — Precision, Recall, F1-score (important due to class imbalance), confusion matrix

## 📊 Results

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | - | - | - | - |
| Random Forest | - | - | - | - |
| XGBoost | - | - | - | - |

*(Fill in your actual metrics here)*

## 🚀 Getting Started

### Prerequisites
```bash
pip install -r requirements.txt
```

### Run the project
```bash
git clone https://github.com/Anand07-ak/fraud-job-detection.git
cd fraud-job-detection
python main.py
```

## 📁 Project Structure

```
fraud-job-detection/
│
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks for EDA & modeling
├── src/                   # Source code (preprocessing, training, evaluation)
├── models/                # Saved trained models
├── requirements.txt
└── README.md
```

## 📈 Future Improvements

- Use deep learning models (LSTM/BERT) for better text understanding
- Deploy as a web app for real-time job posting verification
- Expand dataset with more recent/diverse job postings

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open a pull request.

## 📄 License

This project is licensed under the MIT License.

## 👤 Author

**Anand07-ak**
GitHub: [@Anand07-ak](https://github.com/Anand07-ak)
