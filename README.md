# 🏡 PREDICTION OF HOME PRICES

![preview](/assets/word_cloud_spam_messages.png)

This data science project applies a Multinomial Naive Bayes classifier to detect and classify spam messages. By leveraging probabilistic modeling and natural language processing techniques, the goal is to improve email filtering systems and minimize the impact of unsolicited or malicious content.


## 🔍 Problem

Spam messages are a major issue in digital communication, often containing unwanted or harmful content. The goal of this project is to build a machine learning model that accurately classifies messages as spam or ham based on their text. This helps improve message filtering systems and protects users without losing important information

## 📊 Dataset

- Sourced: [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Nº of registers: 5572 messages
- Features: type, message

## 🛠️ Techniques Used

- Data exploratory analisys (EDA)
- Word tokenization
- Vectorization of tokens
- MultinomialNB
- Tunning of hiperparametros with GridSearchCV

## 📈 Results

- accuracy: 0.97
- ham recall: 0.98
- spam recall: 0.91

## 🧠 Lessons learn

The cleaning of the messages during the tokenization process, such as removing stop words and symbols, had a significant impact on the results by reducing noise in the dataset. Identifying patterns in the data, like message length and the most frequent words, also proved to be strong indicators for classification.

## 🚀 How to run this project

Follow these steps to run the project on your local machine:

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Miguel9Angel/SMS_spam_detector.git
cd SMS_spam_detector
```

### 2️⃣ Requirements
pip install -r requirements.txt

### 3️⃣ Run the notebook
jupyter notebook notebooks/classification_spam.ipynb

## 📁 Repository estructure

```text
HOUSE_PRICE_PREDICTION/
├── assets/
│   └── word_clod_spam_messages.png
├── data/
│   └── SMSSpamCollection
├── notebooks/
│   └── classification_spam.ipynb
├── LICENSE
├── README.md
└── requirements.txt
```

## 📜 Licence

This project is licensed under the [Licencia MIT](./LICENSE).  
You are free to use, modify, and distribute this code, provided that proper credit is given.

--------------------------------------------------------------------------------------

## 🙋 About me

My name is Miguel Angel Soler Otalora, a mechanical engineer with a background in data science and artificial intelligence. I combine the analytical and structured thinking of engineering with modern skills in data analysis, visualization, and predictive modeling.

This project is part of my portfolio to apply for roles as a Data Analyst or Data Scientist, and it reflects my interest in applying data analysis to real-world problems.

📫 You can contact me on [LinkedIn](https://linkedin.com/in/miguel-soler-ml) or explore more projects on [GitHub](https://github.com/Miguel9Angel).