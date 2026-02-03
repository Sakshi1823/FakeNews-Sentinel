# 📰 FakeNews-Sentinel

### **Introduction**
FakeNews-Sentinel is a Machine Learning-powered detection engine designed to identify and classify misinformation in digital news articles. By utilizing Natural Language Processing (NLP) and supervised learning algorithms, the system analyzes linguistic patterns and metadata to distinguish between authentic reporting and fabricated content. This project serves as a foundational tool for building trustworthy information ecosystems.

---

### **🛠️ Tech Stack**

| Layer | Technology |
| :--- | :--- |
| **Language** | Python 3.x |
| **Data Processing** | Pandas, NumPy |
| **Machine Learning** | Scikit-Learn |
| **NLP** | NLTK / TF-IDF Vectorization |
| **Environment** | Jupyter Notebooks / ML Scripts |

---

### **📂 Project Structure**

* **`/ML_Scripts`**: Contains the core logic for the detection engine, including data preprocessing, feature engineering, and model training scripts (Passive Aggressive Classifier / Naive Bayes).
* **`/CSVs`**: The data warehouse containing categorized datasets of labeled news articles used for training and testing model accuracy.
* **`README.md`**: Project documentation and technical overview.

---

### **✨ Key Features**

* **Advanced Text Vectorization:** Implements **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert raw text into high-dimensional numerical data for precise model analysis.
* **Automated Preprocessing:** Features a pipeline for noise reduction, including stop-word removal and punctuation stripping, to improve classification accuracy.
* **Linguistic Pattern Recognition:** Analyzes the "weight" of specific phrases and words commonly found in clickbait and sensationalist media.
* **Performance Metrics:** Evaluates model success using Confusion Matrices and Accuracy Scores to ensure a high rate of true-positive detection.

---

### **🚀 Future Roadmap**
* **Real-time API:** Transitioning the ML scripts into a Flask/FastAPI backend.
* **Agentic Verification:** Integrating with **CrewAI** to allow the system to browse the live web for fact-checking.
