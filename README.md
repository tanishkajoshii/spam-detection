# spam-detection

# 📩 Spam Message Detection using Machine Learning

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** and the **Multinomial Naive Bayes** algorithm.

---

## 📌 Project Overview

Spam messages are a common problem in email and SMS communication. This project builds a text classification model that can automatically detect whether a message is spam or legitimate.

The project uses **TF-IDF Vectorization** to convert text into numerical features and **Multinomial Naive Bayes** for classification.

---

## 🚀 Features

- SMS text preprocessing
- Text cleaning using Regular Expressions
- Label Encoding (Spam = 1, Ham = 0)
- TF-IDF Feature Extraction
- Train-Test Split
- Multinomial Naive Bayes Classifier
- Model Evaluation
- Custom Message Prediction
- Prediction Confidence Score

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Regular Expressions (re)
- Jupyter Notebook

---

## 📂 Dataset

Dataset: **SMS Spam Collection Dataset**

The dataset contains two columns:

| Column | Description |
|---------|-------------|
| v1 | Label (spam / ham) |
| v2 | SMS Message |

Unused columns were removed during preprocessing.

---

## ⚙️ Project Workflow

1. Load Dataset
2. Remove unnecessary columns
3. Encode labels
4. Clean text
   - Convert to lowercase
   - Remove punctuation
   - Remove extra spaces
5. Split dataset into training and testing sets
6. Convert text into TF-IDF vectors
7. Train Multinomial Naive Bayes model
8. Evaluate model
9. Predict new SMS messages

---

## 🧹 Text Preprocessing

The following preprocessing steps were applied:

- Convert text to lowercase
- Remove numbers and punctuation
- Remove special characters
- Remove extra white spaces

Example:

Input:
```
URGENT!! Claim your FREE prize now!!!
```

Output:
```
urgent claim your free prize now
```

---

## 🤖 Machine Learning Model

Algorithm Used:

- **Multinomial Naive Bayes**

Feature Extraction:

- **TF-IDF Vectorizer**
  - English stop words removed
  - Maximum Features = 3000

---

## 📊 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📩 Example Prediction

Input:

```
URGENT! Your account has been suspended. Verify your details immediately.
```

Output:

```
Prediction: Spam
Confidence: 99%
```

Input:

```
Hey, are we still meeting for lunch tomorrow?
```

Output:

```
Prediction: Ham
Confidence: 98%
```

---

## 📁 Project Structure

```
Spam-Message-Detection/
│
├── spam.csv
├── spam.ipynb
├── README.md
└── requirements.txt
```

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Spam-Message-Detection.git
```

Move into the project directory

```bash
cd Spam-Message-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook.

---

## 📋 Requirements

```
numpy
pandas
scikit-learn
matplotlib
jupyter
```

Or install manually:

```bash
pip install numpy pandas scikit-learn matplotlib notebook
```

---



## 👨‍💻 Author

** Tanishka Joshi**

Machine Learning Enthusiast | Data Science Learner

---

## ⭐ If you found this project useful, don't forget to Star the repository!
