# Sentiment Analysis NLP Mini Project

This repository contains an end-to-end **Sentiment Classification** project built using **Natural Language Processing (NLP)** and **Machine Learning** techniques.  
The project preprocesses text data, converts it into numerical vectors using **TF-IDF**, and compares the performance of multiple ML models.

---

## 📌 Project Overview
This mini project performs sentiment analysis on text data with the goal of classifying tweets into the following classes:

- **Positive**
- **Negative**
- **Neutral**

The dataset originally contained an additional class *Irrelevant*, which was later mapped into **Neutral** for better consistency.

---

## 🔧 Tech Stack
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**
- **NLTK** (optional)

---

## 🛠️ Workflow

### 1️⃣ Data Preprocessing
- Renamed columns for consistency  
- Kept only required columns: `text`, `sentiment`  
- Mapped 4 original sentiment classes → 3 classes  
- Removed missing/empty text entries

### 2️⃣ Feature Extraction
Used **TF-IDF Vectorizer**:
- English stopwords  
- Maximum 10,000 features  

### 3️⃣ Model Training
Trained and evaluated the following ML algorithms:
- Logistic Regression  
- Linear SVC  
- Naive Bayes  
- Random Forest  

### 4️⃣ Evaluation
For each model:
- Computed Accuracy  
- Displayed Classification Report  
- Plotted Confusion Matrix  

---

## 📊 Results

| Model                | Accuracy |
|---------------------|----------|
| Random Forest       | 0.9489   |
| Linear SVC          | 0.9129   |
| Logistic Regression | 0.8788   |
| Naive Bayes         | 0.8028   |

### **🏆 Best Model: Random Forest Classifier**

---

## 📈 Visualization
A bar plot compares accuracy across all models for clearer interpretation.

---


