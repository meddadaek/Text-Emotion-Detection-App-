<p align="center">
  <img src="BANNER_FILE_NAME.png" width="80%">
</p>

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

🎯 Usage

Run the Streamlit app:

streamlit run app.py


Then open the app at:

http://localhost:8501/

🧠 How It Works
1. User enters text

The app takes a sentence/paragraph through a Streamlit form.

2. Model Predicts
pipe_lr.predict([text])

3. Confidence & Probabilities

The model outputs:

the predicted emotion

full probability distribution across all emotion classes

4. Visualization

Altair renders a bar chart showing confidence for each emotion.

🎨 UI Preview

Input text area

Two-column result layout

Emoji display next to predicted emotion

Probability plot

📝 Example

Input:

I am really happy today!


Output:

Emotion: joy 😂
Confidence: 0.97

🛠 Model File

The app loads the pre-trained model:

pipe_lr = load("text_emotion.pkl")


Make sure your model file is in the same folder as app.py.

🤝 Contributing

Pull requests are welcome!
Feel free to:

improve model accuracy

try a deep learning model (LSTM/GRU)

enhance UI

deploy to Streamlit Cloud / HuggingFace Spaces

📄 License

This project is licensed under the MIT License.

⭐ Support

If you like this project, consider giving it a star ⭐ on GitHub!
## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/meddadaek/Text-Emotion-Detection-App.git
cd Text-Emotion-Detection-App
