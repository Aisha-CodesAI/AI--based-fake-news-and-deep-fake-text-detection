# AI--based-fake-news-and-deep-fake-text-detection

# 📰 Fake News Detection using AI, Explainable ML & Voice Output

An intelligent Fake News Detection System built using Machine Learning, Gradio, LIME Explainability, and gTTS Voice Output.

This project predicts whether a news headline/article is REAL or FAKE, highlights important words influencing the prediction, and even speaks the result using AI voice output.

---

# 🚀 Features

✅ Detects Fake vs Real News  
✅ Built with Machine Learning  
✅ TF-IDF + Logistic Regression Model  
✅ Interactive Gradio Web Interface  
✅ Explainable AI using LIME  
✅ Voice Output using gTTS  
✅ Confidence Score Prediction  
✅ Highlighted Important Words  
✅ Runs directly in Google Colab

---

# 🧠 Technologies Used

- Python
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Gradio
- LIME
- gTTS
- Pandas
- NumPy
- Joblib

---

# 📂 Project Structure

```bash
Fake-News-Detector/
│
├── FakeNewsDetector.ipynb
├── mini_fake_news.csv
├── baseline_mini.joblib
├── requirements.txt
├── README.md
└── assets/
```

---

# ⚙️ How It Works

## 1️⃣ Dataset Creation

A mini fake news dataset is created containing:
- REAL news
- FAKE news
- UNVERIFIED news

---

## 2️⃣ Text Processing

The news text is converted into numerical features using TF-IDF Vectorization.

```python
TfidfVectorizer()
```

---

## 3️⃣ Model Training

A Machine Learning pipeline is trained using Logistic Regression.

```python
LogisticRegression()
```

---

## 4️⃣ Explainable AI

LIME is used to highlight words that influenced the prediction.

Example:
- Red highlights → Fake indicators
- Green highlights → Real indicators

---

## 5️⃣ Voice Output

The prediction result is converted into speech using gTTS.

```python
gTTS()
```

Example:

> "This news is Fake with 92 percent confidence."

---

## 6️⃣ Web Interface

The entire model is deployed using Gradio.

Users can:
- Paste news text
- Get prediction
- View confidence score
- Listen to voice output

---

# 📸 Demo

## Input

```text
NASA confirms the sun will not rise tomorrow due to cosmic shift
```

## Output

```text
Prediction: FAKE
Confidence: 97%
```

🎤 Voice Output:

> “This news is Fake with 97 percent confidence.”

---

# 🧪 Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Fake-News-Detector.git
cd Fake-News-Detector
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

```bash
python app.py
```

OR run directly in:
- Google Colab
- Jupyter Notebook

---

# 📦 Requirements

```txt
gradio==5.47.2
lime==0.2.0.1
scikit-learn==1.6.1
joblib==1.5.2
gTTS==2.5.4
pandas==2.2.2
numpy==2.0.2
matplotlib==3.10.0
scipy==1.15.3
nltk==3.9.1
```

---

# 💡 Future Enhancements

🚀 Audio Fake News Detection  
🚀 Video Deepfake Detection  
🚀 Real-time News Verification API  
🚀 NLP using Transformers/BERT  
🚀 Multilingual Fake News Detection  
🚀 Live Social Media Analysis  
🚀 AI Fact Checking System

---

# 📊 Machine Learning Pipeline

```text
News Text
   ↓
TF-IDF Vectorization
   ↓
Logistic Regression Model
   ↓
Prediction
   ↓
LIME Explanation
   ↓
Voice Output using gTTS
```

---

# 🔍 Explainable AI

This project uses LIME (Local Interpretable Model-Agnostic Explanations) to make AI predictions understandable and transparent.

Benefits:
- Improves trust in AI
- Shows why news is fake or real
- Makes predictions interpretable

---

# 🌐 Gradio Interface

The Gradio UI allows users to interact with the model easily through a browser.

Interface includes:
- Text Input Box
- Prediction Output
- Confidence Score
- Highlighted Keywords
- Audio Output

---

# 👩‍💻 Author

**Aisha Erum (Eda)**  
AI & ML Enthusiast | CSE-AIML Student | Future AI Startup Founder

GitHub: `Aisha-CodesAI`

---

# ⭐ Project Goal

The goal of this project is to fight misinformation using Artificial Intelligence and Explainable Machine Learning while making AI predictions interactive and user-friendly.

---

# 📜 License

This project is open-source and available under the MIT License.

---

# 🌟 If You Like This Project

⭐ Star the repository  
🍴 Fork the project  
📢 Share with others
