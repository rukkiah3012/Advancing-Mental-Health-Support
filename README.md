# 🧠 Advancing Mental Health Support

An AI-powered web application that analyzes **text and audio inputs** to assess a user’s mental health condition—specifically targeting **depression** and **suicidal tendencies**. This multimodal tool uses Machine Learning and Deep Learning to provide real-time screening, emotional state recognition, and tailored recommendations.

---

## 💡 Project Objective

- Detect mental health issues like **depression** and **suicide risk**.
- Accept input via **typed text** or **recorded/uploaded voice**.
- Use NLP and speech-based ML models for detection.
- Deliver **personalized wellness recommendations**, crisis helplines, and support videos.
- Built using **Streamlit** for real-time and private self-assessment.

---

## 🏗️ Project Architecture

### 🔤 Text Analysis
- **Preprocessing**: Stopword removal, lemmatization, TF-IDF vectorization.
- **Models Used**: Logistic Regression (best), Decision Tree, Random Forest, Multinomial Naive Bayes.

### 🔊 Audio Analysis
- **Features Extracted**: MFCCs, ZCR, Spectral Rolloff, MelSpectrograms.
- **Models Used**:
  - MLP (Multi-Layer Perceptron) for depression detection.
  - CNN + BiLSTM for emotion classification.

### 🧩 Fusion Logic
- A rule-based mechanism integrates both modalities to enhance prediction reliability.

---

## 🧪 Evaluation Metrics

- **Text Classifier Accuracy**: 90.2%
- **Audio Classifier Accuracy**: 93%
- Metrics include: Precision, Recall, F1-Score, and Confusion Matrix.

---

## 🚀 How to Run the App

1. Open the folder in Visual Studio Code: "advancing-mental-health-support"

2.Install required packages pip install streamlit  pandas numpy matplotlib librosa scikit-learn tensorflow

3.Run the app, python -m streamlit run app.py

4.The app will open in your browser at: http://localhost:8501

---

⚙️ Features
Upload and analyze voice recordings.

Detect emotional states: Normal, Sad, Depressed, Suicidal.

Visualize audio waveforms and extracted features.

Simple and user-friendly Streamlit interface.

📊 Technologies Used
Python

Streamlit – Web app framework

Librosa – Audio processing

Scikit-learn – Machine learning models

Pandas and NumPy – Data handling

Matplotlib and Seaborn – Visualization

🧪 Future Scope
Expand the model to support real-time monitoring.

Include demographic filters (e.g., age groups, gender).

Integrate with mobile applications or healthcare platforms.

✨ Author
Developed by Rukkiah Sajeena M and Zaafira A
Final Year B.Tech CSE C Student

📌 License
This project is for educational and research purposes only.

📌 Disclaimer
This project is intended for educational and research purposes only.

