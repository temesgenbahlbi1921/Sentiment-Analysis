# Sentiment Analysis Project

A machine learning and deep learning–based sentiment classification system designed to analyze text data such as movie reviews and social media posts.
This project compares multiple models — including **Naive Bayes, SVM, RNN, and CNN** — to determine the most effective approach for sentiment prediction.

---

## 📌 Project Overview

This project focuses on classifying text into **positive**, **negative**, or **neutral** sentiments. It includes a complete pipeline from data preprocessing to model evaluation, along with visualizations and example usage.

---

## 🎯 Objectives

* Build a **robust sentiment analysis model**.
* Clean and preprocess raw text data.
* Evaluate multiple ML and deep learning models.
* Provide a simple **interface for inference**.
* Document the workflow for learning and reproducibility.

---

## 📂 Dataset

The project uses:

* **IMDB Movie Reviews Dataset** (50,000 labeled reviews)
* Additional social media-style datasets (optional)

---

## 🧹 Data Preprocessing

Key steps include:

* Removing noise (special characters, punctuation, stopwords)
* Tokenization
* Lemmatization / stemming
* Normalization (lowercasing, formatting)
* Vectorization using **TF-IDF** or padded sequences

---

## 🤖 Models Implemented

### **Machine Learning**

* **Naive Bayes**
* **Support Vector Machine (SVM)**

### **Deep Learning**

* **Recurrent Neural Network (RNN)**
* **Convolutional Neural Network (CNN)**

Each model is trained, validated, and compared using standardized metrics.

---

## 📊 Model Performance Summary

| Model           | Accuracy | Notes                              |
| --------------- | -------- | ---------------------------------- |
| **Naive Bayes** | 0.85     | Strong baseline performance        |
| **SVM**         | 0.89     | Best classical ML model            |
| **RNN**         | 0.51     | Underperformed; struggled to learn |
| **CNN**         | 0.87     | Best deep learning model           |

Visualizations of training accuracy for CNN and RNN are included in the project.

---

## 🛠️ Tools & Libraries

* **Python**, **NumPy**, **Pandas**
* **NLTK**
* **Scikit-learn**
* **TensorFlow** / **Keras**
* **Matplotlib**

---

## 📁 Project Structure

```
├── data/
├── notebooks/
├── models/
├── src/
│   ├── preprocessing.py
│   ├── train_ml.py
│   ├── train_dl.py
│   └── predict.py
├── results/
└── README.md
```

---

## 🚀 Example Usage

```python
from predict import predict_sentiment

text = "This movie was absolutely wonderful!"
print(predict_sentiment(text))
```

---

## 📈 Visualizations

The notebook includes:

* **CNN accuracy plot**
* **RNN accuracy plot**
* **Comparison of ML vs DL models**

---

## 🧪 Evaluation

Models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
  Cross-validation ensures generalizability.

---

## 📌 Future Improvements

* Improve RNN performance
* Add more diverse training datasets
* Build a richer user interface
* Explore transformer-based models (BERT, DistilBERT, RoBERTa)

---

## 📝 Authors

* Temesgen Bahlbi
---

## 📚 References

* IMDB Dataset
* Scikit-learn documentation
* TensorFlow & Keras API references

---

Feel free to fork, contribute, or open issues!
