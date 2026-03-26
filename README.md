# 🚀 NLP Preprocessing Engine

## 📌 Overview
In real-world NLP systems, raw text data is often noisy, inconsistent, and unstructured.  
This project builds a **robust and reusable NLP preprocessing pipeline** that transforms messy text into clean, meaningful tokens suitable for machine learning models.

---

## 🎯 Objectives
- Design a scalable NLP preprocessing pipeline
- Handle real-world noise (URLs, emojis, repeated characters, etc.)
- Perform token-level analytics
- Build production-quality, clean Python code

---

## ⚙️ Features
✅ Lowercasing text  
✅ Removal of numbers, URLs, and email patterns  
✅ Removal of punctuation and extra spaces  
✅ Handling repeated characters (e.g., *soooo → so*)  
✅ Tokenization  
✅ Removal of short tokens (≤ 2, except "no", "not")  
✅ Token analytics (count, unique words, average length)  
✅ Frequency analysis using `collections.Counter`  
✅ Full pipeline implementation  
✅ Error handling (empty input, only emojis, only numbers)

---

## 🧠 Conceptual Understanding
- Case sensitivity impacts vocabulary size  
- Stopword removal reduces noise but may harm meaning in some tasks  
- Stemming vs Lemmatization trade-off between speed and accuracy  

---

## 🧪 Sample Input
```text
"I absolutely looooved this product 😍😍"
