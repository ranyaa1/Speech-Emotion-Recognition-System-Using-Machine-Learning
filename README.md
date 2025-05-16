# 🎧 Vocal Emotion Recognition with SVM & Random Forest

This project focuses on classifying human emotions from speech using audio features and machine learning models. It leverages **Support Vector Machines (SVM)** and **Random Forest (RF)** to analyze and predict emotions from `.wav` audio files.

---



## 📁 Dataset

We used the **RAVDESS Emotional Speech Audio** dataset available on Kaggle:  
🔗 [RAVDESS Dataset on Kaggle](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)

It includes speech recordings of actors expressing a variety of emotions (happy, sad, angry, neutral, etc.).


## 🎯 Objective

- Extract relevant audio features from speech.
- Train and evaluate SVM and Random Forest models.
- Compare their performance for emotion classification.

---

## 🎵 Feature Extraction

Features extracted from audio files using **Librosa** include:

- MFCCs (Mel-Frequency Cepstral Coefficients)
- Chroma Frequencies
- Zero-Crossing Rate
- Root Mean Square (RMS) Energy
- Spectral Centroid
- Mel Spectrogram

All extracted features are compiled into a CSV file for training and evaluation.

---

## 🤖 Models

Two models were implemented and evaluated:

- **SVM (Support Vector Machine)** with RBF kernel
- **Random Forest Classifier**

Metrics used:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📊 Results
| Model              | Accuracy |
|-------------------|----------|
| Support Vector Machine (SVM) | **97%**     |
| Random Forest (RF)          | **94%**     |

> Results may vary depending on the dataset and preprocessing steps.



## 🛠️ Tools & Libraries

- Python 3.x
- Librosa
- NumPy & Pandas
- Scikit-learn
- Matplotlib & Seaborn

---
