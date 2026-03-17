# 📰 Fake News Detection Web App

A simple yet effective **Fake News Detection** system built using **Machine Learning** and **Streamlit**. This application predicts whether a given news article is **Real** or **Fake** based on its content.

---

## 📌 Problem Statement

In today’s digital world, the spread of **fake news** has become a serious concern. Misinformation can influence public opinion, manipulate behavior, and cause real-world consequences. To tackle this, we need a system that can intelligently classify news articles as either genuine or fabricated using machine learning.

---

## 📖 Project Description

This project focuses on building a machine learning model that learns the writing patterns of both real and fake news articles and uses that learning to detect whether a new article is legitimate or not. The model is integrated into a **Streamlit web application** to provide a user-friendly interface for quick predictions.

Users simply paste any news article into the input box, and the app will classify it as either **"Real"** or **"Fake"** based on the model's output.

---
## 🎬 Demo Video

[![Demo Video Thumbnail](https://raw.githubusercontent.com/Chandrashekar0123/Fake-news-detection/main/assets/thumbnail.png)](https://raw.githubusercontent.com/Chandrashekar0123/Fake-news-detection/main/Fake%20-News-Detection.mp4)

Click the image above to watch the demo video.

✅ The video walkthrough includes:
- GUI interface overview
- Model input and output demonstration
- Real-time fake news detection

---

## 🧠 Theory (How it Works)

1. **Text Preprocessing**: The text is cleaned to remove noise like punctuation, numbers, and stop words.
2. **Feature Extraction**: A vectorizer converts text into numerical format the machine can understand.
3. **Classification**: A pre-trained **Random Forest Classifier** processes the vector and makes a prediction.
4. **Prediction Output**: The result is displayed on the web interface.

---

## 💻 How to Run the App

```bash
# Clone the repository
git clone https://github.com/Chandrashekar0123/Fake-news-detection.git
cd Fake-news-detection

# Install dependencies
pip install -r requirements.txt

# Run the web app
streamlit run app.py
```

---

## 🛠️ Tech Stack

- **Python**
- **Scikit-learn**
- **Streamlit**
- **Joblib** (for model and vectorizer serialization)

---

## 📁 Project Structure

```
Fake-news-detection/
├── app.py                # Main web app file
├── model.pkl             # Trained ML model
├── vectorizer.jb         # Saved text vectorizer
├── requirements.txt      # Dependency file
└── .gitignore            # Ignoring large files (e.g., datasets)
```

---

## ✨ Features

- 🧾 Paste any news article to get a prediction
- 🧠 Machine Learning-powered analysis
- ⚡ Fast and responsive UI with Streamlit
- 🎯 High accuracy with Random Forest Classifier

---


## 🙌 Credits

Developed with ❤️ by **Chandrashekar**  
🔗 GitHub: [Chandrashekar0123](https://github.com/Chandrashekar0123)

---

## ⭐ Show Some Love

If you found this project useful, give it a ⭐ and share it with others!
