# 🧠 Text Emotion Detection App  
A machine-learning powered **Emotion Classification Web App** built with **Streamlit**, using a trained model (`text_emotion.pkl`) to detect emotions from text such as:

- 😠 Anger  
- 😨 Fear  
- 🤗 Love  
- 😂 Joy  
- 😔 Sadness  
- 😮 Surprise  

This project uses traditional NLP preprocessing + an ML model (Logistic Regression / SVM / RNN / etc. depending on training) to classify emotions with probability visualization.

---

## 🚀 Features

✔ Detects the dominant emotion in user input  
✔ Shows an emoji for the predicted emotion  
✔ Displays model confidence score  
✔ Visualizes probabilities for all emotion classes (Altair bar chart)  
✔ Clean, interactive Streamlit UI  

---

## 🧩 Project Structure


├── app.py # Streamlit app
├── text_emotion.pkl # Trained emotion classifier model
├── README.md # Project documentation
└── requirements.txt # Python dependencies

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/meddadaek/Text-Emotion-Detection-App.git
cd Text-Emotion-Detection-App
