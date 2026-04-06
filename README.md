# 🧠 Text Sentiment Classification using RNN & LSTM

## 📌 Project Overview

This project focuses on **Sentiment Analysis** using Deep Learning techniques such as **Recurrent Neural Networks (RNN)** and **Long Short-Term Memory (LSTM)**.

The goal is to classify text data (e.g., movie reviews) into:

* ✅ Positive
* ❌ Negative
* ⚖️ Neutral

This project is part of the course **Deep Learning Architectures and Techniques (ETMMDL274)**.

---

## 🎯 Objectives

* Understand sequential data processing using deep learning
* Implement RNN and LSTM models for text classification
* Compare performance of RNN vs LSTM
* Analyze the effect of sequence length and embeddings

---

## 📂 Dataset

We used the **IMDB Movie Reviews Dataset**:

* 50,000 reviews (balanced dataset)
* 25,000 for training
* 25,000 for testing

---

## ⚙️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy, Pandas
* Matplotlib
* Scikit-learn
* NLTK

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing

* Convert text to lowercase
* Remove punctuation & stopwords
* Tokenization
* Vocabulary creation
* Convert text to sequences
* Padding sequences to fixed length

---

### 2️⃣ Model Architectures

#### 🔹 RNN Model

* Embedding Layer
* SimpleRNN Layer
* Dense Layer (Sigmoid)

#### 🔹 LSTM Model

* Embedding Layer
* LSTM Layer
* Dense Layer

---

### 3️⃣ Training

* Loss Function: Binary Crossentropy
* Optimizer: Adam
* Epochs: 5–10

---

### 4️⃣ Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score

---

## 📊 Results

| Model | Accuracy | Performance |
| ----- | -------- | ----------- |
| RNN   | ~82%     | Moderate    |
| LSTM  | ~88–90%  | High        |

### 📈 Observations

* LSTM performs better than RNN
* Handles long-term dependencies efficiently
* Reduces vanishing gradient problem

---

## 📉 Graphs Included

* Training vs Validation Loss (RNN & LSTM)
* Accuracy Curves
* Performance Comparison

---

## 🧠 Key Concepts

### 🔹 RNN

* Processes sequential data
* Suffers from short-term memory

### 🔹 LSTM

* Uses gates (Input, Forget, Output)
* Captures long-term dependencies
* More accurate for NLP tasks

---

## ▶️ How to Run the Project

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### Step 2: Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run Notebook / Script

```bash
python main.py
```

---

## 📦 Requirements

```
tensorflow
numpy
pandas
matplotlib
scikit-learn
nltk
```

---

## 📁 Project Structure

```
📦 sentiment-analysis
 ┣ 📜 main.py
 ┣ 📜 model.py
 ┣ 📜 preprocessing.py
 ┣ 📜 requirements.txt
 ┣ 📜 README.md
 ┗ 📊 graphs/
```

---

## ⚠️ Common Issues

### ❌ TensorFlow Import Error

✔ Fix:

```bash
pip install tensorflow
```

### ❌ VS Code Interpreter Issue

✔ Fix:

* Select correct Python interpreter
* Restart VS Code

---

## 🚀 Future Improvements

* Use GRU model
* Add attention mechanism
* Use pre-trained embeddings (Word2Vec, GloVe)
* Deploy as web app

---

## 📚 Learning Outcomes

* Implement deep learning for NLP
* Understand sequence modeling
* Compare RNN and LSTM performance

---

## 👨‍💻 Author

**Kartik Kumar**
MCA (AI/ML) Student

---

## ⭐ Acknowledgment

* TensorFlow Documentation
* IMDB Dataset
* Academic course material

---

## 📌 Conclusion

This project demonstrates that **LSTM significantly outperforms RNN** in sentiment classification tasks due to its ability to retain long-term contextual information.

---

⭐ *If you found this helpful, consider giving this repo a star!*
