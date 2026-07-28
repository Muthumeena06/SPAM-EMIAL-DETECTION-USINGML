# 📧 Spam Email Detection using Machine Learning

## 📌 Project Overview

Spam emails are unwanted messages that may contain advertisements, phishing links, or malicious content. This project develops a **Spam Email Detection System** using **Machine Learning** to classify emails as **Spam** or **Ham (Not Spam)**.

The project uses **TF-IDF Vectorization** for text feature extraction and compares multiple machine learning algorithms to identify the best-performing model. The **Support Vector Machine (SVM)** achieved the highest accuracy and was selected as the final model.

---

## 🎯 Objectives

* Detect whether an email is Spam or Ham.
* Preprocess email text for machine learning.
* Compare different machine learning algorithms.
* Select the best-performing model.
* Save the trained model for future predictions.

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Pickle

---

## 📂 Dataset

The project uses the **Spam Email Dataset (`spam.csv`)**.

Dataset Columns:

* **v1** → Label (Spam/Ham)
* **v2** → Email Message

---

## 🔄 Project Workflow

```
Dataset
   ↓
Data Preprocessing
   ↓
TF-IDF Feature Extraction
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Best Model Selection
   ↓
Save Model
   ↓
Load Model
   ↓
Predict New Email
```

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses and visualizations were performed:

* Display Dataset
* Head & Tail
* Dataset Shape
* Data Types
* Missing Values
* Duplicate Removal
* Unique Values
* Target Variable Distribution
* Correlation Matrix
* Heatmap
* Histogram
* Count Plot
* Box Plot
* Scatter Plot
* Pair Plot
* KDE Plot
* Violin Plot
* Bar Plot
* Pie Chart
* Outlier Detection using IQR

---

## ⚙️ Feature Engineering

* Message Length
* Word Count
* Character Count

---

## 🧹 Data Preprocessing

* Remove duplicate records
* Encode labels using LabelEncoder
* TF-IDF Vectorization
* Train-Test Split

---

## 🤖 Machine Learning Algorithms

The following models were trained and compared:

* Logistic Regression
* Multinomial Naive Bayes
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

After comparison, **Support Vector Machine (SVM)** achieved the best performance and was selected as the final model.

---

## 💾 Model Saving

The trained model and TF-IDF vectorizer are saved using Pickle.

Generated files:

* `svm_spam_model.pkl`
* `tfidf_vectorizer.pkl`

---

## 🚀 How to Run the Project

1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the `spam.csv` dataset.
4. Run all cells in order.
5. Train the model.
6. Save the model.
7. Test with new email messages.

---

## 📁 Project Structure

```
Spam-Email-Detection/
│
├── Spam_Email_Detection.ipynb
├── spam.csv
├── svm_spam_model.pkl
├── tfidf_vectorizer.pkl
├── README.md
└── requirements.txt
```

---

## 📈 Sample Prediction

**Input**

```
Congratulations! You have won a free iPhone.
Click here to claim your prize.
```

**Output**

```
Spam Email
```

---

## 📌 Future Enhancements

* Deploy using Streamlit
* Build a Flask/Django web application
* Use Deep Learning (LSTM/BERT)
* Improve accuracy with larger datasets
* Real-time email filtering

---

## 👩‍💻 Author

**Muthumeena G**

B.E. Computer Science and Engineering

---

## 📄 License

This project is developed for educational and learning purposes.
