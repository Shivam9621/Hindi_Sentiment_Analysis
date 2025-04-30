# 🇮🇳 Hindi Sentiment Analysis using Deep Learning

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-red)

This project performs **sentiment analysis on Hindi text** using a deep learning model (LSTM) and provides an interactive **web interface** built with **Streamlit**.

---

## 🚀 Live Demo

🎥 [Watch Demo Video](https://your-demo-link.com)  
🌐 [Try Web App (optional if hosted)](https://your-streamlit-link.com)

---

## 📁 Project Contents

- `Hindi_sentiment_analysis.ipynb` – Jupyter notebook for model training, evaluation, and saving artifacts.
- `my_model.h5` – Trained LSTM model file.
- `tokenizer.pickle` – Tokenizer to convert Hindi text to sequences.
- `label_encoder.pickle` – Encodes/decodes sentiment labels.
- `app.py` – Streamlit web app for real-time sentiment prediction.
- `requirements.txt` – List of required Python packages.
- `README.md` – Project documentation.

---

## 💡 Features

- Classifies Hindi sentences into:
  - ✅ Positive
  - ❌ Negative
  - ⚪ Neutral
- LSTM model using TensorFlow/Keras
- Cleaned and preprocessed Hindi data
- Model + tokenizer + label encoder saved for inference
- User-friendly Streamlit interface for real-time input and predictions

---

## 🛠️ Installation

### 🔧 Clone the repository

```bash
git clone https://github.com/yourusername/hindi-sentiment-analysis.git
cd hindi-sentiment-analysis
