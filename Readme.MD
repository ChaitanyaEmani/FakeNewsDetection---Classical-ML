# 📰 Fake News Detection — Logistic Regression (Colab)

A classical Machine Learning project to detect fake news using **Logistic Regression**. The model was built and trained entirely in **Google Colab**, leveraging NLP techniques to preprocess news headlines and content.

---

## 📌 Project Overview

With the growing threat of misinformation, detecting fake news is more critical than ever. This project uses **Logistic Regression** — a simple yet effective algorithm — along with **TF-IDF** and NLP preprocessing to classify news as real or fake.

---

## ✅ Key Features

- Built and trained using **Google Colab**
- Applied **text preprocessing** (stopwords removal, stemming)
- Combined `title` and `text` columns for better context
- Used **TF-IDF Vectorization**
- Achieved **high accuracy (~96%)** on test data
- Fast and lightweight solution for small to medium datasets

---

## 🛠️ Tech Stack

- Python (Colab environment)
- Scikit-learn
- Pandas & NumPy
- NLTK (Natural Language Toolkit)

---

## 📑 Dataset

- Source: [Fake and Real News Dataset – Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
- Two CSVs combined:
  - `Fake.csv`
  - `True.csv`

---

## 📊 Model

| Model              | Accuracy |
|-------------------|----------|
| LogisticRegression| ~96%     |

---

## ⚙️ Steps Performed

1. **Combined** `title` and `text` columns into one `news` column
2. **Labeled** real and fake news
3. Applied **text cleaning & stemming**
4. Converted to numerical features using **TF-IDF**
5. Trained **Logistic Regression** classifier
6. Evaluated using accuracy and confusion matrix
7. Tested with real-world examples (limitations observed)

---

## ⚠️ Limitations

- Cannot generalize well to **real-world web articles** without retraining on a broader dataset
- Performance may drop on informal or short news snippets
- Classical ML struggles with deep semantic understanding

---

## 💡 Future Improvements

- Replace Logistic Regression with **BERT** or other transformer-based models
- Fine-tune on real-world datasets (news API or scraped data)
- Build a full **Streamlit UI** or deploy using HuggingFace Spaces

---

## 🧑‍💻 Author

**Chaitanya Emani**

---

## ⭐ Like this project?

If this project helped you understand fake news detection, consider giving it a ⭐ on GitHub.
