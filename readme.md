# 📰 Fake News Detection Using Machine Learning and LSTM

This project is a **Fake News Detection System** built using **Python**, **scikit-learn**, and **TensorFlow (Keras)**.
It classifies news articles as **True** or **Fake** based on text data using both **classical Machine Learning models** and a **Deep Learning (LSTM)** approach.

---

## 🚀 Overview

Fake news detection is an important problem in today’s digital world.
This project combines traditional NLP preprocessing, TF-IDF feature extraction, and multiple classification algorithms to accurately predict the authenticity of news headlines and content.

The models used include:

- **Naïve Bayes**
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Gradient Boosting**
- **Random Forest**
- **Extra Trees**
- **Long Short-Term Memory (LSTM)** neural network
- **Voting Classifier (ensemble)**

---

---

## 🧩 Features

✅ Preprocesses and cleans text data (stopword removal, stemming, punctuation removal)✅ Converts text into TF-IDF feature vectors✅ Builds and evaluates **multiple ML models**✅ Trains a **LSTM-based neural network** for sequence classification✅ Combines models using a **Voting Classifier** for improved performance✅ Displays multiple evaluation metrics:

- Precision
- Recall
- F1-Score
- Hamming Loss
- Accuracy
- Log Loss

✅ Accepts **user input** to test custom news headlines in real-time.
-----------------------------------------------------------------

## 🧠 Model Summary

### 1️⃣ Machine Learning Models

The project trains and compares performance across:

- Multinomial Naïve Bayes
- Logistic Regression
- Support Vector Machine (SVM)
- Extra Trees Classifier
- Gradient Boosting Classifier
- Random Forest Classifier

### 2️⃣ Deep Learning Model (LSTM)

A **Long Short-Term Memory (LSTM)** neural network is built using Keras, featuring:

- Embedding Layer
- SpatialDropout1D for regularization
- Two stacked LSTM layers
- Dense layer with **sigmoid** activation for binary classification
- **EarlyStopping** to prevent overfitting

### 3️⃣ Ensemble Learning

A **Voting Classifier** combines all machine learning models using **hard voting** to make a final decision.

---

## 🧮 Evaluation Metrics

The following metrics are calculated for every classifier:

| Metric                 | Description                                    |
| ---------------------- | ---------------------------------------------- |
| **Precision**    | Accuracy of positive predictions               |
| **Recall**       | Model’s ability to capture all true positives |
| **F1-Score**     | Harmonic mean of precision and recall          |
| **Hamming Loss** | Fraction of labels incorrectly predicted       |
| **Log Loss**     | Evaluates probabilistic predictions            |
| **Accuracy**     | Overall correctness of the model               |

---


## 🧩 Future Improvements

* 🧬 Add pre-trained transformer models (e.g., BERT, RoBERTa)
* 📈 Build a Streamlit or Flask web interface
* 🧾 Integrate explainability tools like LIME or SHAP
* 💾 Deploy on cloud platforms (AWS / Hugging Face Spaces)
