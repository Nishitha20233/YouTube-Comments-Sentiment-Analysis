# YouTube-Comments-Sentiment-Analysis
Built a sentiment analysis model using YouTube API, TF-IDF, and machine learning to classify user comments and visualize sentiment trends.

📊 YouTube Comment Sentiment Analysis (Flask + ML)

This project analyzes YouTube video comments using Machine Learning and Flask Web App.
It extracts comments using the YouTube Data API, preprocesses them, applies a TF-IDF + ML model, and classifies them into:

✅ Positive
😐 Neutral
❌ Negative

🚀 Features

✅ Fetch comments from any YouTube video using URL

✅ Clean and preprocess text (stopwords, punctuations, stemming)

✅ TF-IDF feature extraction

✅ Machine Learning-based sentiment classification

✅ Flask web interface to display sentiments

✅ Separate lists for positive, neutral, and negative comments

🛠️ Tech Stack
Component	Technology Used

Language--Python

Framework--Flask

ML Model--Pickle (.pkl)

Feature Extraction--TF-IDF

API--YouTube Data API (v3)

Frontend--HTML, CSS

Libraries--NLTK, Regex, sklearn

🔑 Setup Instructions
✅ 1. Clone the repository

git clone https://github.com/your-username/youtube-sentiment-analysis.git
cd youtube-sentiment-analysis

✅ 2. Create a virtual environment

python -m venv venv
source venv/Scripts/activate  # Windows
source venv/bin/activate      # Mac/Linux

✅ 3. Install Dependencies

pip install -r requirements.txt


Or manually:

pip install flask nltk scikit-learn google-api-python-client pickle-mixin

✅ 4. Download NLTK resources

import nltk
nltk.download('stopwords')

✅ 5. Add your YouTube API Key

In app.py, replace:

api_key = "YOUR_API_KEY"

▶️ Run the Project

python app.py


Then open:

http://127.0.0.1:5000

🌐 Usage

1️⃣ Paste any YouTube video URL
2️⃣ Click “Analyze”
3️⃣ Sentiments are displayed in three sections:

✅ Positive Comments

😐 Neutral Comments

❌ Negative Comments

🧠 ML Model Details

Trained using cleaned YouTube comments

TF-IDF Vectorizer used

Model saved as .pkl file

Predictions mapped as:

2 → Positive

1 → Neutral

0 → Negative

🛡️ Future Enhancements

🔹 Emoji Support

🔹 Multilingual Comment Handling

🔹 Bar/Pie Chart Visualizations

🔹 Downloadable Report

🔹 Authentication & Dashboard

📜 License

This project is open-source and free to use for learning and research.
