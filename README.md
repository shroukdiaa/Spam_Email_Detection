# 📧 Spam Email Detection using Machine Learning

## 📌 Project Overview

This project focuses on building a machine learning model to automatically detect **spam emails**.
The system analyzes email text and classifies it as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) and machine learning algorithms.

The goal of this project is to improve email security and automate spam filtering.

---

## 🚀 Features

* Text preprocessing and cleaning
* Feature extraction using **TF-IDF**
* Training multiple machine learning models
* Model comparison and evaluation
* High accuracy spam detection
* API deployment for real-time predictions

---

## 🧠 Machine Learning Models Used

The following models were trained and evaluated:

* Support Vector Machine (SVM)
* Random Forest
* Logistic Regression (optional)

The models were compared based on:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 📊 Dataset

The dataset contains labeled email messages classified into two categories:

* **Spam** → Unwanted or malicious emails
* **Ham** → Legitimate emails

Typical dataset columns:

| Column | Description           |
| ------ | --------------------- |
| text   | Email message content |
| label  | Spam or Ham           |

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF Vectorizer
* Machine Learning Algorithms
* FastAPI (for deployment)

---

## 🛠 Project Workflow

1. **Data Collection**
2. **Data Cleaning & Preprocessing**
3. **Text Vectorization using TF-IDF**
4. **Train Machine Learning Models**
5. **Evaluate Models**
6. **Model Comparison**
7. **Deploy the Best Model as an API**

---

## 📈 Model Evaluation

Evaluation metrics used:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

The **SVM model achieved the highest performance** in detecting spam emails.

---

## 🔌 API Deployment

The best-performing model was deployed as an API using **FastAPI**.

Example request:

```
POST /predict
```

Example input:

```json
{
  "email": "Congratulations! You won a free prize. Click here now!"
}
```

Example output:

```json
{
  "prediction": "Spam"
}
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/spam-email-detection.git
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run the API

```
uvicorn app:app --reload
```

### 4️⃣ Test the model

Send a POST request with an email message to the API.

---

## 📷 Example Prediction

Input:

```
Congratulations! You've won a free iPhone. Click here now!
```

Output:

```
Spam
```

---

## 👩‍💻 Author

**Shrouk Diaa**
Computer Science & Artificial Intelligence Student
Ahram Canadian University

Interested in:

* Machine Learning
* Artificial Intelligence
* Cybersecurity
