# 📚 Plagiarism Detection System using Machine Learning

## 📌 Overview

This project is a Machine Learning-based Plagiarism Detection System that identifies whether a given text is plagiarized or original. The system uses Natural Language Processing (NLP) techniques and Machine Learning algorithms to analyze text and classify it as plagiarism or non-plagiarism.

---

## 🚀 Features

- Text preprocessing using NLTK
- Stopword and punctuation removal
- TF-IDF feature extraction
- Multiple Machine Learning models for comparison
- Plagiarism prediction on user input
- Simple web interface using Flask

---

## 🛠️ Technologies Used

- Python
- Flask
- NLTK
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Pickle

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Random Forest Classifier
3. Naive Bayes
4. Support Vector Machine (SVM)

The models were compared based on their performance metrics such as accuracy, precision, recall, and F1-score.

---

## 🔄 Project Workflow

1. Load Dataset
2. Text Preprocessing
   - Lowercase Conversion
   - Punctuation Removal
   - Stopword Removal
3. Feature Engineering using TF-IDF
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Save Trained Model
8. Deploy using Flask

---

## 📂 Project Structure

```text
├── app.py
├── dataset.csv
├── model.pkl
├── tfidf.pkl
├── templates/
│   └── index.html
├── static/
├── notebook.ipynb
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/plagiarism-detection-system.git
cd plagiarism-detection-system
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

---

## 📊 Feature Engineering

TF-IDF (Term Frequency–Inverse Document Frequency) is used to convert text data into numerical feature vectors that can be processed by Machine Learning models.

---

## 🎯 Project Objective

The objective of this project is to automate plagiarism detection by leveraging Machine Learning and NLP techniques, reducing manual effort and improving text originality assessment.

---

## 📈 Future Improvements

- Deep Learning Models
- BERT-based Semantic Similarity
- Real-time Document Comparison
- Improved Dataset Size and Diversity
- Advanced Paraphrase Detection

---

## 👨‍💻 Author

**Muhammad Maaz**

Machine Learning & Data Science Student

---

## 📄 License

This project is developed for educational and academic purposes.
