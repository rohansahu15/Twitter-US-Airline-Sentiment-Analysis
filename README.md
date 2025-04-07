# 🐦✈️ Twitter US Airline Sentiment Analysis

This project aims to analyze and classify **public sentiment** towards US airlines based on tweets. By applying **Natural Language Processing (NLP)** techniques and machine learning models, we predict whether a tweet expresses a **positive** or **negative** sentiment.

---

## 🔧 Tools & Libraries Used

- **Python**
- **NumPy**, **Pandas**
- **Matplotlib** (for visualization)
- **Scikit-learn** (for ML models)
- **NLTK** (for text preprocessing)

---

## 💡 Project Highlights

- Developed a sentiment analysis model to classify tweets related to US airlines as **positive** or **negative**
- Applied **Logistic Regression** and **Support Vector Machine (SVM)** for classification
- Achieved strong performance by combining robust preprocessing and reliable ML algorithms

---

## 📊 Dataset

- Raw Twitter data containing tweets about US airlines
- Features include tweet text, airline name, and timestamp
- Target variable: **Sentiment** (`positive`, `negative`)

> 📌 You can use the [Kaggle US Airline Sentiment Dataset](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment) if you're replicating this project.

---

## 🔄 Data Preprocessing

- Removed noise: hashtags, mentions, special characters, URLs
- Converted all text to lowercase
- Removed stopwords
- Performed **tokenization** and **lemmatization**
- Handled missing values and cleaned tweet text

---

## 🤖 Machine Learning Models

| Model              | Description                        |
|-------------------|------------------------------------|
| Logistic Regression | Fast baseline with solid accuracy |
| SVM (Linear Kernel) | High-performance for text data    |

---

## 📈 Evaluation Metrics

- **Accuracy**
- **Precision / Recall**
- **F1 Score**
- **Confusion Matrix**
- **ROC Curve (optional)**

---
