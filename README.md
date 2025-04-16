# Phising_url_detector
A Flask-based web application that detects phishing URLs using machine learning. It extracts 15+ technical and content-based features from the given URL and applies a trained model to classify it as phishing or legitimate. Includes PCA and domain analysis for accuracy

---

## 🚀 Features

- Extracts 15+ handcrafted features from URLs
- Domain age & expiration-based analysis using WHOIS
- Checks for shortened URLs, suspicious words, unicode, and more
- HTML/JS content behavior analysis (iframe, mouseover, forwarding)
- Uses PCA for dimensionality reduction
- Trained ML model using PyCaret
- Simple UI for user input via browser

---

## 🧠 How it Works

1. **Feature Extraction:**  
   Extracts URL length, depth, presence of symbols, keywords, domain data, and content behavior.

2. **Model Prediction:**  
   A trained PyCaret model classifies the input as `Phishing` or `Legitimate`.

3. **Frontend:**  
   Basic HTML form that accepts a URL and displays the result with a probability score.

---

## 🧰 Tech Stack

- Python
- Flask
- PyCaret
- WHOIS
- httpx
- PCA (Scikit-learn)
- HTML/CSS (Frontend)

---

## 📦 Project Structure

1. Clone the repository:
https://github.com/Yogasathya/Phising_url_detector.git


2.Install dependencies:
pip install -r requirements.txt


3.Run the Flask app:
python app.py


4.Visit `http://127.0.0.1:5000` in your browser


## 🧪 Future Improvements

- Add REST API support
- Improve UI with URL highlighting
- Integrate real-time scanning with browser extensions


