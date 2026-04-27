<h1 align="center">🛡️ FakeNews-Sentinel</h1>

<p align="center">
  <b>NLP-powered misinformation detection engine — classifies news articles as real or fake using machine learning</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/NLTK-NLP-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
</p>

---

## What This Does ??

FakeNews-Sentinel is an ML classification engine that takes a news article as input and predicts whether it is real or fabricated. It uses **TF-IDF vectorization** to convert raw text into numerical features and runs it through a **Passive Aggressive Classifier** — a fast online-learning algorithm well-suited for large text datasets.

The system preprocesses raw text (stop-word removal, punctuation stripping) and uses linguistic pattern recognition to flag the kind of sensationalist phrasing common in misinformation.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Python 3.x |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-Learn — Passive Aggressive Classifier, Naive Bayes |
| NLP | NLTK, TF-IDF Vectorization |
| Data | Labeled CSV datasets (real vs fake news) |
| Environment | Jupyter Notebooks + ML Scripts |

---

## 📂 Project Structure

```
FakeNews-Sentinel/
│
├── ML_Scripts/         # Core engine — preprocessing, feature engineering, model training
├── CSVs/               # Labeled datasets for training and testing
└── README.md
```

---

## ⚙️ How It Works

1. **Data Loading** — labeled CSV datasets of real and fake news articles are loaded via Pandas
2. **Preprocessing** — noise reduction pipeline: stop-word removal, punctuation stripping, lowercasing
3. **Vectorization** — TF-IDF converts text into high-dimensional numerical vectors
4. **Training** — Passive Aggressive Classifier is trained on the vectorized data
5. **Evaluation** — model performance measured via Confusion Matrix and Accuracy Score

---

## ✨ Key Features

- TF-IDF vectorization for precise linguistic analysis
- Automated preprocessing pipeline — no manual cleaning needed
- Tested with Passive Aggressive Classifier and Naive Bayes (compare both)
- Performance evaluation via Confusion Matrix and Accuracy Score
- Modular ML scripts — easy to extend with new models

---

## 🚀 Roadmap

- [ ] Flask/FastAPI REST API wrapper for real-time predictions
- [ ] Browser extension for on-the-fly article scanning
- [ ] CrewAI integration for live web fact-checking

---

## 🏃 Run Locally

```bash
git clone https://github.com/Sakshi1823/FakeNews-Sentinel.git
cd FakeNews-Sentinel
pip install pandas numpy scikit-learn nltk
# Open Jupyter or run scripts from ML_Scripts/
```

---

