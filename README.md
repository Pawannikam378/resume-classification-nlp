# Resume Classification using Natural Language Processing (NLP)

## 📌 Project Overview

This project builds a machine learning model to automatically classify resumes into different job categories using Natural Language Processing (NLP).

Recruitment platforms receive thousands of resumes for different job roles. Manually screening them is time-consuming. This system helps automate the process by predicting the most relevant job category based on the resume text.

The model analyzes resume content and assigns it to one of several job domains such as **Information Technology, HR, Finance, Engineering, Healthcare, Sales, and more**.

---

## 📊 Dataset

The dataset contains **2400+ resumes** collected through web scraping.

Each resume is available in both **text and PDF format**.

### Dataset Columns

| Column      | Description                        |
| ----------- | ---------------------------------- |
| ID          | Unique identifier for each resume  |
| Resume_str  | Resume text in plain string format |
| Resume_html | Resume content in HTML format      |
| Category    | Job category the resume belongs to |

### Job Categories

The dataset contains **24 job categories**, including:

HR, Designer, Information-Technology, Teacher, Advocate, Business-Development, Healthcare, Fitness, Agriculture, BPO, Sales, Consultant, Digital-Media, Automobile, Chef, Finance, Apparel, Engineering, Accountant, Construction, Public-Relations, Banking, Arts, Aviation

---

## 🎯 Objectives

* Build an NLP model that classifies resumes into job categories
* Convert textual resume data into numerical features
* Train a machine learning classifier
* Evaluate model performance using classification metrics

---

## ⚙️ Project Workflow

1. Load and explore the dataset
2. Clean resume text (remove special characters, convert to lowercase)
3. Convert text into numerical vectors using **TF-IDF Vectorization**
4. Encode job categories into numerical labels
5. Split dataset into training and testing sets
6. Train classification models
7. Evaluate predictions using precision, recall, and F1-score

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab

---

## 🤖 Machine Learning Models

The following models were implemented:

### Logistic Regression

Baseline classification model used for multi-class text classification.

### Random Forest Classifier

Ensemble learning method used to capture complex patterns in resume text.

---

## 📈 Model Performance

Example performance metrics from Logistic Regression:

| Metric            | Value |
| ----------------- | ----- |
| Accuracy          | 64%   |
| Weighted F1 Score | 0.64  |
| Macro F1 Score    | 0.58  |

The model performs well for categories with sufficient training data but struggles with classes that have very few examples.

---

## 🔎 Key Learnings

* Handling real-world **text data**
* Applying **TF-IDF feature engineering**
* Multi-class classification
* Model evaluation using precision, recall, and F1-score
* Importance of dataset balance in machine learning

---

## 🚀 Future Improvements

* Use **SVM (Support Vector Machine)** for better text classification
* Increase TF-IDF features with n-grams
* Apply **Deep Learning (BERT / Transformers)**
* Build a **web application for resume screening**

---

## 📂 Project Structure

```
resume-classification-nlp
│
├── resume_classification.ipynb
├── README.md
└── requirements.txt
```

---

## 👨‍💻 Author

**Pawan Nikam**

Interested in:

* Data Science
* Artificial Intelligence
* Cybersecurity
* Embedded Systems
