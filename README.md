# AI Resume Analyzer & Job Recommendation System

## 📌 Overview
AI Resume Analyzer is a Flask-based web application that analyzes resumes using Natural Language Processing (NLP) and Machine Learning techniques. 

The system extracts structured information from uploaded resumes and provides intelligent job role recommendations.

---

## 🚀 Features
- 📄 PDF Resume Parsing using PyPDF2
- 🧠 Resume Category Prediction using Random Forest
- 💼 Job Recommendation System
- 📧 Extracts Name, Email, Phone Number
- 🛠 Skills Extraction using NLP techniques
- 🎓 Education Extraction
- 🌐 Web Interface for Resume Upload and Real-time Analysis

---

## 🛠 Tech Stack
- Python
- Flask
- Machine Learning
- TF-IDF Vectorization
- Random Forest Classifier
- Natural Language Processing (NLP)
- HTML
- CSS

---

## 📊 Machine Learning Details
- Used TF-IDF for feature extraction
- Trained Random Forest models for:
  - Resume Category Prediction
  - Job Recommendation
- Integrated trained ML models into Flask web application for real-time predictions

---

## 📁 Project Structure
AI-Resume-Analyzer/
│── app.py
│── templates/
│── models/
│── Extracted Information And Parsing.ipynb
│── Job Recommendation.ipynb
│── Resume Category Prediction.ipynb
│── requirements.txt
│── README.md

---

## ⚙️ How to Run Locally

1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Run the application:
   python app.py
4. Open in browser:
   http://127.0.0.1:5000

---

## 📌 Note
Pre-trained model files (.pkl) are excluded due to GitHub file size limitations.  
They can be regenerated using the provided Jupyter notebooks.

---

## 👨‍💻 Author
Ayush Pandey  
B.Tech CSE (2025)  
Full Stack Developer | Machine Learning Enthusiast
