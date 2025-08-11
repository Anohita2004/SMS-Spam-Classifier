<h1 align='center'> SMS-Spam-Classifier </h1>
<h2 align='center'> https://sms-spam-classifier-21.streamlit.app//</h2>

<br>
<p align="center"> <img src='https://github.com/tejred213/SMS-Spam-Classifier/assets/86062873/af47243a-75a7-4029-9686-073ccd65ca0c'></p>
<br>

![Python Version](https://img.shields.io/badge/Python-3.10-green)
![Contributions welcome](https://img.shields.io/badge/Contributions-Welcome-yellow)
[![NLTK Version](https://img.shields.io/badge/NLTK-3.6-orange.svg)](https://www.nltk.org/)
[![Streamlit Version](https://img.shields.io/badge/Streamlit-1.15.0-red.svg)](https://www.streamlit.io/)
[![scikit-learn Version](https://img.shields.io/badge/scikit--learn-0.24.2-lightbrown.svg)](https://scikit-learn.org/)



This is a repository containing code for an SMS spam classifier built using the Multinomial Naive Bayes algorithm and NLTK (Natural Language Processing Toolkit). The classifier is implemented using supervised learning techniques and can effectively classify SMS messages as either spam or non-spam.

## Requirements
- Python 3.6 or higher
- NLTK
- Scikit-learn
- Streamlit

## Installation
Clone the repository:
```shell
git clone https://github.com/tejred213/SMS-Spam-Classifier.git
```

Install the required dependencies:
```shell
pip install -r requirements.txt
```
## Usage
Make sure you have the NLTK stopwords corpus downloaded. If not, open a Python shell and run the following commands:
```shell
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```

To start the Streamlit app:
```shell
streamlit run app.py
```
## Screenshot
![image](https://github.com/tejred213/SMS-Spam-Classifier/assets/86062873/049ba5bc-8904-48ab-a4b8-15b390f3359c)


![image](https://github.com/tejred213/SMS-Spam-Classifier/assets/86062873/0796dffb-e967-4f4f-b76b-90feedf60730)

## Dataset
The Dataset used in this application is downloaded from kaggle : https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
