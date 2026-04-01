# 🧾 SMS Spam Detection System

## 📌 Project Overview

This project implements a **Spam Detection System** that classifies SMS messages as **Spam** or **Not Spam (Ham)** using Machine Learning techniques. The system is built using Python and leverages the scikit-learn library.

---

## 🎯 Objective

To develop a model that can automatically identify whether a given message is spam or not based on its content.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* scikit-learn

---

## 📂 Dataset

* Dataset used: **SMS Spam Collection Dataset**
* Source: [Kaggle Dataset Link](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?utm_source=chatgpt.com)
* The dataset contains labeled SMS messages:

  * `ham` → Not Spam
  * `spam` → Spam

---

## 🧠 Methodology

### 1. Data Preprocessing

* Removed unnecessary columns
* Renamed columns to `label` and `message`
* Converted labels:

  * Ham → 0
  * Spam → 1

---

### 2. Feature Extraction

* Used **TF-IDF Vectorization**
* Converts text data into numerical format
* Removes stopwords and assigns importance to words

---

### 3. Model Used

* **Multinomial Naive Bayes**
* Suitable for text classification problems
* Works based on probability

---

### 4. Training & Testing

* Dataset split into:

  * 80% Training
  * 20% Testing

---

### 5. Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score

---

## 📊 Results

* **Accuracy:** ~96.6%
* High precision in detecting spam messages
* Effective classification of normal (ham) messages

---

## 🚀 How to Run

1. Install dependencies:

```bash
pip install pandas scikit-learn
```

2. Download dataset and place it in project folder

3. Run the Python script:

```bash
python spam_detection.py
```

---

## 🧪 Sample Test Cases

### Spam Example:

```
URGENT! You have won a FREE prize. Call now
```

### Not Spam Example:

```
Hey, are we meeting today?
```

---

## 📌 Key Features

* Simple and efficient implementation
* High accuracy (~97%)
* Real-world application (email/SMS filtering)
* Easy to understand and extend

---

## 🔮 Future Improvements

* Use Deep Learning models (LSTM, BERT)
* Build a GUI or web interface
* Improve spam recall using advanced techniques
* Deploy as an API

---

## 👨‍💻 Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be used to effectively classify messages. The model performs well and can be extended for real-world spam filtering applications.

---
