# Fake-News-Detection
Fake News Detection Using Python
# 📰 Fake News Detection using Machine Learning

This project aims to detect fake news articles using machine learning techniques, specifically focused on binary classification of news as **"Real" or "Fake"**. The model is trained using natural language processing (NLP) and TF-IDF vectorization, and results are presented using a Flask-based web interface.

📄 This repository includes the complete IEEE-style project report created in Overleaf, documenting the system design, methodology, and analysis.

---

## 📌 Project Overview

- Designed a machine learning model to classify news articles as **Real** or **Fake**.
- Used **TF-IDF vectorization** and **Passive Aggressive Classifier** for high-speed binary classification.
- Accuracy achieved: **~94.63%** on test data.
- Deployed basic output via **Flask** to display results in a web browser.
- Developed and documented the report using **LaTeX on Overleaf**.

---

## 🔧 Tools & Technologies

- Python (Pandas, Scikit-learn, NLTK)
- TF-IDF Vectorizer
- Passive Aggressive Classifier
- Flask (for browser output)
- Overleaf (LaTeX) – for report writing

---

## ⚙️ Workflow Summary

1. **Preprocessing**: Cleaned news dataset by removing stopwords and punctuations.
2. **Vectorization**: Applied TF-IDF to convert text into numerical format.
3. **Model Training**: Used Passive Aggressive Classifier for binary classification.
4. **Evaluation**: Confusion matrix and classification report used for accuracy checking.
5. **Deployment**: Result displayed in browser using Flask – user inputs news text, model returns "Real" or "Fake".

---

## 📁 Repository Contents

- `Fake-News-Report.pdf` – Final project report (IEEE format)
- `model_code/` *(Optional)* – Python files (if you want to upload code in future)
- `README.md` – This file

---

## 🔬 Applications

- **Social Media Platforms**: Flagging and filtering fake content
- **News Organizations**: Verifying articles before publishing
- **Politics & Finance**: Preventing misinformation during elections or market-sensitive events
- **Healthcare**: Detecting medical misinformation

---

## 👩‍💻 Team Members

- Jyoti Indore (Roll No. 18) – Report Writing & Documentation Lead  
- Ashwini Chemte (Roll No. 08) – Model Implementation & Code Integration  
- **Under the guidance of:** Dr. Anita Morey  
- **Institution:** Usha Mittal Institute of Technology, SNDT Women’s University  

---

## 📈 Future Scope

- Integrate image/video fake detection (deepfake detection)
- Expand model to support **multi-language detection**
- Upgrade backend to use **transformer-based models** like BERT
- Build full-stack app with live news feed classification

---

⭐ *This project was submitted as a major academic project in fulfillment of the B.Tech in Artificial Intelligence (2024–2025).*  
