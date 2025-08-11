# SMS-Spam-Classifier
# 📧 Email Spam Classifier  

**Live App:** [https://sms-spam-classifier-21.streamlit.app/](https://sms-spam-classifier-21.streamlit.app/)  

![Python Version](https://img.shields.io/badge/Python-3.10-green)  
![Contributions welcome](https://img.shields.io/badge/Contributions-Welcome-yellow)  
[![NLTK Version](https://img.shields.io/badge/NLTK-3.6-orange.svg)](https://www.nltk.org/)  
[![Streamlit Version](https://img.shields.io/badge/Streamlit-1.15.0-red.svg)](https://www.streamlit.io/)  
[![scikit-learn Version](https://img.shields.io/badge/scikit--learn-0.24.2-lightbrown.svg)](https://scikit-learn.org/)  

---

## 📌 Overview  
This project is a **spam detection web app** that classifies incoming text messages as **Spam** or **Not Spam** using **Natural Language Processing (NLP)** and the **Multinomial Naive Bayes** algorithm.  
It leverages **NLTK** for text preprocessing and **scikit-learn** for model training, with a sleek **Streamlit** frontend for real-time predictions.  

---
## Pipeline:
![App Screenshot](https://github.com/Anohita2004/SMS-Spam-Classifier/blob/main/sms_spam_pipeline.png)


## 🚀 Features  
- ✅ Classifies messages into **Spam** or **Ham**  
- ✅ Interactive **web interface** via Streamlit  
- ✅ Uses **Bag of Words + TF-IDF Vectorization**  
- ✅ **Pre-trained model** for instant predictions  
- ✅ Easy deployment to **Heroku** or Streamlit Cloud  

---

## 📂 Project Structure  
.
├── app.py # Streamlit app entry point
├── sms-spam-detection.ipynb # Jupyter notebook for training & EDA
├── spam.csv # Dataset (Kaggle SMS Spam Collection)
├── vectorizer.pkl # Saved TF-IDF vectorizer
├── model.pkl # Trained Naive Bayes model
├── nltk.txt # NLTK data dependencies
├── setup.sh # Streamlit server setup
├── Procfile # Deployment configuration
└── README.md # Documentation

---
##  Screenshots

![App Screenshot](https://github.com/user-attachments/assets/7d0a6e03-8d43-435b-9e52-ad31fbdd00dd)
![App Screenshot](https://github.com/Anohita2004/SMS-Spam-Classifier/blob/main/spammm_2.png)


## 🛠 Installation & Setup  

1️⃣ **Clone this repository**  
```bash
git clone https://github.com/yourusername/email-spam-classifier.git
cd email-spam-classifier
2️⃣ Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Download NLTK data

python
Copy
Edit
import nltk
nltk.download('stopwords')
nltk.download('punkt')
4️⃣ Run the app locally

bash
Copy
Edit
streamlit run app.py
📊 Dataset
Source: Kaggle - SMS Spam Collection Dataset

Total messages: 5,574

Labels: ham (legit) / spam (junk)

Format: CSV with two columns – label & message

