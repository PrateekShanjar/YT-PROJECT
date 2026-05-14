# 🎯 YouTube Sentiment Analysis System  
### AI-Powered Real-Time Comment Analysis for YouTube

Transform YouTube comments into meaningful insights using **Machine Learning** and **Natural Language Processing (NLP)**. This project fetches live comments from YouTube videos and predicts whether the audience reaction is **Positive, Negative, or Neutral** through an interactive full-stack web application.

Built with **Python, Flask, React, Scikit-learn, and YouTube Data API**.

---

## ✨ Key Highlights

🚀 Real-time YouTube comment extraction  
🧠 AI-based sentiment prediction using NLP  
📊 Interactive dashboard for analysis  
⚡ Fast Flask REST API integration  
🎨 Modern React frontend interface  
📈 High accuracy sentiment classification model  
🔍 Text preprocessing & TF-IDF vectorization  
🌐 Fully responsive web application  

---

# 🛠️ Tech Stack

### 💻 Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### ⚙️ Backend
- Python
- Flask
- REST APIs

### 🤖 Machine Learning & NLP
- Scikit-learn
- TF-IDF Vectorizer
- NLP Text Processing
- Sentiment Classification Model

### 🔗 APIs
- YouTube Data API v3

---

# 📂 Project Structure

```bash
YT-PROJECT/
│
├── backend/
│   ├── app.py
│   ├── model.pkl
│   ├── vectorizer.pkl
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── dataset/
├── notebooks/
└── README.md
```

---

# ⚡ Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/PrateekShanjar/YT-PROJECT.git
cd YT-PROJECT
```

---

## 2️⃣ Install Backend Dependencies

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Start Backend Server

```bash
python app.py
```

Backend will run on:

```bash
http://127.0.0.1:5000
```

---

## 4️⃣ Run Frontend

```bash
cd frontend
npm install
npm start
```

Frontend will run on:

```bash
http://localhost:3000
```

---

# 🔑 Configure YouTube API

1. Open Google Developer Console  
2. Enable **YouTube Data API v3**  
3. Generate API Key  
4. Add your API key in backend configuration

```python
API_KEY = "YOUR_API_KEY"
```

---

# 🧠 How It Works

### 📌 Step 1 — Fetch Comments
The application extracts comments from YouTube videos using the YouTube Data API.

### 📌 Step 2 — NLP Processing
Text data is cleaned using:
- Tokenization
- Stopword Removal
- Lowercasing
- Text Cleaning

### 📌 Step 3 — Feature Extraction
TF-IDF Vectorization converts text into numerical features.

### 📌 Step 4 — Sentiment Prediction
The trained ML model predicts:
- Positive 😊
- Negative 😠
- Neutral 😐

---

# 📊 Model Performance

| Metric | Score |
|---|---|
| Accuracy | 92% |
| Precision | 91% |
| Recall | 90% |
| F1-Score | 91% |

---

# 🎥 Example

### Input Comment
```text
"This video is incredibly helpful and well explained!"
```

### Prediction
```text
Positive 😊
```

---

# 🎯 Real-World Applications

- Social Media Analytics
- Audience Feedback Analysis
- Brand Reputation Monitoring
- YouTube Content Evaluation
- Opinion Mining
- Marketing Insights

---

# 🔮 Future Enhancements

✅ Multi-language sentiment analysis  
✅ Emotion detection system  
✅ Deep Learning models (LSTM/BERT)  
✅ Real-time analytics dashboard  
✅ Spam & toxic comment detection  
✅ Cloud deployment support  

---

<img width="1912" height="954" alt="image" src="https://github.com/user-attachments/assets/b33606aa-697f-4973-a266-cdea80bfc593" />




<img width="1908" height="954" alt="image" src="https://github.com/user-attachments/assets/4398a91e-acba-4383-87fb-672481d529e1" />



<img width="1905" height="948" alt="image" src="https://github.com/user-attachments/assets/007bbf9d-a659-4bf5-8270-9445ad551aef" />



<img width="1906" height="991" alt="image" src="https://github.com/user-attachments/assets/c1b1cde1-3ea9-4ddc-b5e5-9ff8bf3525e9" />



<img width="1919" height="1001" alt="image" src="https://github.com/user-attachments/assets/7ad16092-9d4a-4fa3-a1a0-b0f3bec4b2f9" />



<img width="1919" height="973" alt="image" src="https://github.com/user-attachments/assets/df5b8e80-f78a-41d2-9f17-becfab024e42" />

