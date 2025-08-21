🔐 Phishing URL Detection Web Application
A Python-based web app to detect whether a URL is legitimate ✅ or phishing ❌, powered by machine learning.
The app is built on Streamlit for an intuitive interface and leverages a feature-rich dataset of URLs.

🚀 Features
🔎 URL Classification
Predicts whether a given URL is legitimate or phishing

Utilizes machine learning models (Logistic Regression and Linear Regression)

Highlights common phishing indicators such as redirections, suspicious symbols, and unsafe domains

📊 Feature Extraction
Extracts 30+ lexical, domain-based, and content-based features from a URL, such as:

URL length

Presence of @ symbols or IP addresses

Use of redirections and multiple subdomains

HTTPS/SSL validation

🖥️ Interactive Web Interface
Designed with Streamlit for ease of use

Simple text input to check any URL

Real-time results with prediction probability and confidence score

🧑💻 Model Training & Evaluation
Train your own ML model using phishing_dataset.csv

Evaluate using accuracy, precision, recall, and F1-score

Easily save and load models via .pkl files for deployment

📂 Project Structure
text
phishing_detector_app/
│
├── app.py             # Streamlit web application
├── main.py            # Model training and evaluation script
├── requirements.txt   # Dependencies and required libraries
└── README.md          # Documentation
⚙️ Setup & Installation
Clone the repository

bash
git clone https://github.com/yourusername/phishing-url-detector.git
cd phishing-url-detector
Install dependencies

bash
pip install -r requirements.txt
Run the application

bash
streamlit run app.py
🎯 Usage
Open the provided local URL from Streamlit in your browser.

Enter a URL into the input field.

Click “Check URL” to analyze.

Output example:

✅ Legitimate

❌ Phishing
(includes explanation and confidence score)

📦 Requirements
Python 3.8+

Libraries:

scikit-learn

pandas

numpy

streamlit

joblib
