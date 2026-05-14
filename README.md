🎬 YouTube Sentiment Analysis System

A full-stack AI-powered web application that analyzes YouTube comments and classifies them into Positive, Negative, or Neutral sentiments using Natural Language Processing (NLP) and Machine Learning.

Built using Python, Flask, React, Scikit-learn, and YouTube Data API. The system fetches real-time YouTube comments, processes textual data using NLP techniques, and predicts sentiment with high accuracy.

GitHub Repository:
YT-PROJECT Repository

🚀 Features

✅ Fetch real-time YouTube comments using YouTube Data API
✅ Sentiment classification using Machine Learning
✅ NLP preprocessing pipeline for text cleaning
✅ Interactive React frontend dashboard
✅ REST API integration using Flask backend
✅ Real-time prediction results
✅ Sentiment visualization and analysis
✅ Responsive UI design

🛠️ Tech Stack
Frontend
React.js
HTML
CSS
JavaScript
Backend
Python
Flask
Scikit-learn
Pandas
NumPy
NLP & ML
Natural Language Processing (NLP)
TF-IDF Vectorization
Sentiment Classification Model
APIs
YouTube Data API
📂 Project Structure
YT-PROJECT/
│
├── backend/
│   ├── app.py
│   ├── model.pkl
│   ├── vectorizer.pkl
│   ├── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│
├── dataset/
│   ├── comments.csv
│
├── notebook/
│   ├── model_training.ipynb
│
└── README.md
⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/PrateekShanjar/YT-PROJECT.git
cd YT-PROJECT
2️⃣ Create Virtual Environment
python -m venv venv
Activate Environment
Windows
venv\Scripts\activate
Linux/Mac
source venv/bin/activate
📦 Install Backend Dependencies
pip install -r requirements.txt
▶️ Run Backend Server
python app.py

Backend runs on:

http://127.0.0.1:5000
🌐 Run Frontend
cd frontend
npm install
npm start

Frontend runs on:

http://localhost:3000
🔑 YouTube API Setup
Go to Google Developer Console
Enable YouTube Data API v3
Generate API Key
Add your API key in the backend configuration file

Example:

API_KEY = "YOUR_API_KEY"
🧠 Machine Learning Workflow
NLP Preprocessing
Lowercasing
Stopword removal
Tokenization
Text cleaning
TF-IDF feature extraction
Model Training
Dataset preprocessing
Feature vectorization
Sentiment classification
Accuracy evaluation
📊 Example Output
Input Comment
"This video is absolutely amazing!"
Predicted Sentiment
Positive 😊
📈 Model Performance
Metric	Score
Accuracy	92%
Precision	91%
Recall	90%
F1-Score	91%
🎯 Use Cases
YouTube Comment Analysis
Social Media Monitoring
Brand Reputation Analysis
Audience Feedback Evaluation
Content Performance Analysis
Opinion Mining
🔮 Future Improvements
Multi-language sentiment analysis
Deep Learning integration using LSTM/BERT
Real-time analytics dashboard
Emotion detection support
Spam comment filtering
Cloud deployment support

👨‍💻 Author

Developed by Prateek Shanjar & Team as an AI-powered YouTube Sentiment Analysis platform.





<img width="1912" height="954" alt="image" src="https://github.com/user-attachments/assets/b33606aa-697f-4973-a266-cdea80bfc593" />




<img width="1908" height="954" alt="image" src="https://github.com/user-attachments/assets/4398a91e-acba-4383-87fb-672481d529e1" />



<img width="1905" height="948" alt="image" src="https://github.com/user-attachments/assets/007bbf9d-a659-4bf5-8270-9445ad551aef" />



<img width="1906" height="991" alt="image" src="https://github.com/user-attachments/assets/c1b1cde1-3ea9-4ddc-b5e5-9ff8bf3525e9" />



<img width="1919" height="1001" alt="image" src="https://github.com/user-attachments/assets/7ad16092-9d4a-4fa3-a1a0-b0f3bec4b2f9" />



<img width="1919" height="973" alt="image" src="https://github.com/user-attachments/assets/df5b8e80-f78a-41d2-9f17-becfab024e42" />

