# Advancing-Mental-Health-Support
# 🧠 Advancing Mental Health Support

An AI-powered web application that analyzes **text and audio inputs** to assess a user’s mental health condition—specifically targeting **depression** and **suicidal tendencies**. This multimodal tool uses Machine Learning and Deep Learning to provide real-time screening, emotional state recognition, and tailored recommendations.

## 💡 Project Objective

- Detect mental health issues like **depression** and **suicide risk**.
- Accept input via **typed text** or **recorded/uploaded voice**.
- Use NLP and speech-based ML models for detection.
- Deliver **personalized wellness recommendations**, crisis helplines, and support videos.
- Built using **Streamlit** for real-time and private self-assessment.

## 🏗️ Project Architecture

### 🔤 Text Analysis
- **Preprocessing**: Stopword removal, lemmatization, TF-IDF vectorization.
- **Models Used**: Logistic Regression (best), Decision Tree, Random Forest, Multinomial Naive Bayes.

### 🔊 Audio Analysis
- **Features Extracted**: MFCCs, ZCR, Spectral Rolloff, MelSpectrograms.
- **Model**: MLP (Multi-Layer Perceptron) for depression detection, CNN+BiLSTM for emotion classification.

### 🧩 Fusion Logic
- A rule-based mechanism integrates both modalities to enhance prediction reliability.

## 🧪 Evaluation Metrics
- **Text Classifier Accuracy**: 90.2%
- **Audio Classifier Accuracy**: 93%
- Evaluation includes: Precision, Recall, F1-score, and Confusion Matrix.

## 💻 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/RukkiahSajeena/advancing-mental-health-support.git
   cd advancing-mental-health-support
   
## 🚀 How to Run the App

### 1. Install dependencies:

```bash
pip install -r requirements.txt
python -m streamlit run app.py
The app will open in your browser at http://localhost:8501

##⚙️ Features
-Upload and analyze voice recordings

-Detect emotional states: Normal, Sad, Depressed, Suicidal

-Visualize audio waveforms and extracted features

-Simple and user-friendly Streamlit interface


   
