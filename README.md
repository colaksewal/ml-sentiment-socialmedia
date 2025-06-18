# 📊 Social Media-Based Sentiment Analysis

This project focuses on **sentiment analysis** of user-generated content from social media platforms. The goal is to classify texts as **positive** or **negative** using machine learning algorithms and improve model performance, especially on imbalanced datasets.

---

## 📌 Project Objectives

- Classify social media texts into **positive (0)** or **negative (1)** sentiment
- Compare the performance of various machine learning models
- Address **class imbalance** using advanced data augmentation techniques
- Ensure scalability and accuracy on large text datasets

---

## 🧠 Algorithms Used

To evaluate model effectiveness and reliability, we implemented and compared the following algorithms:

- ✅ Logistic Regression  
- 🌲 Random Forest  
- 🌿 Decision Tree  
- 📈 Support Vector Machine (SVM)  
- 🧮 Naive Bayes  

---

## 🧾 Dataset Information

- **Source**: Texts collected from social media platforms  
- **Features**:
  - `Text`: User-generated content
  - `Label`: 0 = Positive, 1 = Negative
- **Note**: The dataset was imbalanced (fewer negative examples)

To address this, we applied **SMOTE (Synthetic Minority Over-sampling Technique)**, which helped balance the dataset by generating synthetic negative examples.

---

## 🛠️ Preprocessing & Techniques

- Text cleaning and normalization
- Tokenization
- Vectorization (TF-IDF, CountVectorizer, or embeddings)
- **SMOTE** for minority class augmentation
- Model evaluation via accuracy, precision, recall, and F1-score

---

## 🧪 Evaluation

All models were evaluated using standard metrics. SMOTE significantly improved classification performance, especially recall for the negative class. The comparison helped us select the most robust algorithm for sentiment prediction on social media data.

