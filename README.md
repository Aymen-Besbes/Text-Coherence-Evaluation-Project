# Text Coherence Evaluation Project

## 🚀 Project Overview
This project is an academic project and aims to evaluate text coherence at multiple levels (phrase, paragraph, and document) using transformer-based embeddings (BERT, GPT-2, RoBERTa) and distance metrics (cosine, Euclidean, Manhattan). It also includes a machine learning approach to predict coherence scores.

---

## ✨ Features
1. **Embedding Generation**:
   - BERT, GPT-2, and RoBERTa embeddings for text.
2. **Similarity Metrics**:
   - Cosine similarity, Euclidean distance, Manhattan distance.
3. **Coherence Levels**:
   - Phrase-level, paragraph-level, and document-level coherence.
4. **ML Integration**
   - Classifiers: Naive Bayes and SVM.
   - Features: BoW, TF-IDF, Word2Vec.

---

## 🛠 Methodology
### 1. 🗃️ Data Collection
- Collected 9 paragraphs, each with 3–4 sentences.
- Constructed a dataframe containing **all possible sentence pairs** per paragraph.

### 2. 🧑‍🏫 Human Annotation
- Sentence pairs were manually annotated with coherence scores from **1 (low)** to **5 (high)**.
- Annotation based on semantic similarity and logical flow.

### 3. 🧹 Preprocessing
- Standard NLP preprocessing:
  - Lowercasing
  - Removing special characters
  - Tokenization
  - Lemmatization
  - Stopword removal

### 4. 🧠 Feature Extraction & Similarity Computation
- Used transformer models to generate sentence embeddings.
- Computed similarity using:
  - **Cosine similarity**
  - **Euclidean distance**
  - **Manhattan distance**

---

## 📈 Some Results
### Transformer-Based Coherence Approach
| Model       | Cosine Similarity (Mean) | Euclidean Similarity (Mean) | Manhattan Similarity (Mean) |
|-------------|--------------------------|-----------------------------|-----------------------------|
| BERT        | 3.0                     | 3.0                        | 4.0                         |
| GPT-2       | 3.0                      | 3.0                         | 4.0                         |
| RoBERTa     | 3.0                      | 3.0                         | 4.0                         |

### Machine Learning Approach
| Model       | Vectorizer | Accuracy | F1 Score | Recall   |
|-------------|------------|----------|----------|----------|
| Naive Bayes | TF-IDF     | 0.15     | 0.25     | 0.15     |
| SVM         | BoW        | 0.12     | 0.3      | 0.3      |
| SVM         | TF-IDF     | 0.12     | 0.3      | 0.3      |
| SVM         | WordToVec  | 0.11     | 0.25     | 0.25     |

⚠️ Note: Low performance is due to the limited size (n=150) and subjectivity in annotation.


---

## 📜 License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---
## 📅 Project Timeline

- **Original creation date:** February 2024  
- **Upload to GitHub:** May 2025

---
## 📬 Contact
Author: Aymen Besbes

Email: Aymen.besbes@outlook.com | Aymen.besbes@ensi-uma.tn

LinkedIn: https://www.linkedin.com/in/aymen-besbes
