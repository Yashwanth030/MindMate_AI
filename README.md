![MINDMATE AI](https://github.com/user-attachments/assets/c371dfff-d657-4050-993e-9c4738489d8a)

---
# MindMate_AI – AI-Powered Mental Health Support System

MindMate_AI is an intelligent web-based system that empowers users to assess and manage their mental health through interactive tools such as facial emotion detection, depression screening, sentiment analysis, and AI-driven chatbot support.

> Built using Flask, Python, Deep Learning & NLP  
> Developed as part of a 6-month research & development internship  
> Scroll down to view snapshots of the working UI 

---

## Overview

Mental health issues like anxiety, stress, and depression often go unnoticed due to stigma, inaccessibility, or lack of awareness. MindMate_AI is designed to bridge this gap using artificial intelligence:

- Real-time **facial emotion recognition**
- Standardized **PHQ-9 depression test**
- A **sentiment-aware chatbot** for basic guidance
- Automatic **mental health classification**
- **Personalized self-care suggestions** based on user responses

---

## Snapshots of Working UI

> Below are key UI screens of the MindMate_AI system:

### Login, Home & About Pages

| Login Page | Home Page | About Page |
|------------|-----------|------------|
|![login](https://github.com/user-attachments/assets/7e79087e-42b4-4b6e-92b4-d085b137ec6a) | ![homepage](https://github.com/user-attachments/assets/43e90b2c-8b79-4004-9f74-47d6dafb0ab9)| ![about](https://github.com/user-attachments/assets/bab52b67-2b8d-4569-946e-488a8e2f5752)|

---

### Depression Test & Results

| PHQ-9 Questionnaire |sentimental Description|
|---------------------|----------------------|
|![questions](https://github.com/user-attachments/assets/db8e3fa9-eb6a-42ff-90c0-1e5cef3be8d7)|![result of description](https://github.com/user-attachments/assets/6b8d773e-e35c-4ab1-a5ef-87ea85ec8742)|

---

### Chatbot & Emotion Detection using WebCam

| Chatbot Interface | Emotion: Happy | Emotion: Angry |
|-------------------|----------------|----------------|
| ![chatbot](https://github.com/user-attachments/assets/9099531d-c5f7-4fbe-9d77-16d85081facb)| ![happy](https://github.com/user-attachments/assets/3a1737f3-74cc-4e21-babe-0e08f019c7a5) | ![angry](https://github.com/user-attachments/assets/d75a41e7-591d-492f-a664-0e5acbbcf674) |

---

### Accuracy 

|Sentimental analusis model accuracy |
|----------------|
| ![accuracy and report](https://github.com/user-attachments/assets/93e4ef7c-6e65-435c-978b-80558f7e4ab9)|

---

## Core Features

- User registration and login (MySQL-based)
- Live **Facial Emotion Detection** FER-2013 dataset trained using categorical crossentropy ADAM optimizer CNN & OpenCV to perfrom via webcam.
- **PHQ-9 (Questionnaire)** – Clinical depression assessment, user selects answers for 9 questions, each mapped to scores (0–3).Total score is interpreted (e.g., mild, moderate, severe depression).Based on results,it shows personalized self-care suggestions. Personalized well-being **recommendations** based on score.
- **AI Chatbot** – NLP-driven chatbot using custom 20 intents dataset of user queries and trained TF-IDF + SVM/RF model using scikit learn.
- **Sentiment & Text Classification** – TF-IDF + ML for mental state detection used 274 labeled statements.
- **Excel Export** – Depression results & emotion logs saved using pandas for analysis.
  
---
## Technologies Used

**Frontend:**
- HTML, CSS, Bootstrap, JavaScript
**Backend:**
- Flask, Python

**AI/ML:**
- TensorFlow/Keras, Scikit-learn, OpenCV, NLTK, Imbalanced-learn

**Database:**
- MySQL + Flask-MySQLdb

**Others:**
- dotenv, joblib, pickle, Pandas, NumPy, imutils
---

