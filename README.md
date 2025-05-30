# 📧 SMS Spam Detection using NLP

This project focuses on detecting SMS spam messages using Natural Language Processing (NLP) techniques. The goal is to classify messages as either **Spam** or **Ham** (not spam).

## 📂 Project Structure

The project is organized into multiple Jupyter notebooks, each handling different stages of the process:

- **Data Exploration & Cleaning**
- **Text Preprocessing**
- **Feature Extraction (Vectorization)**
- **Model Training & Evaluation**
- **Final Results & Insights**

## 📊 Dataset

The dataset used is the **SMS Spam Collection Dataset**, publicly available on Kaggle:

🔗 [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

To use the dataset:

1. Download it from the link above.
2. Extract and place the file (`spam.csv` or similar) in the appropriate folder (e.g., `data/`).

> **Note:** The dataset is not included in this repository due to size and licensing considerations.

## 🧠 Reference Notebook

This project was heavily inspired by the following Kaggle notebook:

🔗 [SMS Spam Detection with NLP by Dk Talaicha](https://www.kaggle.com/code/dktalaicha/sms-spam-detection-with-nlp#Vectorization)

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib / Seaborn
- Google Colab  

## ✅ Features

- Data cleaning and preprocessing
- Text vectorization (TF-IDF / CountVectorizer)
- Classification models (Naive Bayes)
- Evaluation metrics: Accuracy, Precision, Recall, F1-score
