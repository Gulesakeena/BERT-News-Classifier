# 📰 BERT News Topic Classification

## 📌 Project Overview
This project is part of the **AI/ML Engineering Internship (Task 1)** by DevelopersHub Corporation.

The goal is to build a **News Topic Classification system** using a fine-tuned **BERT (bert-base-uncased)** model. The model classifies news articles into four categories:

- World
- Sports
- Business
- Sci/Tech

---

## 🎯 Objective
To fine-tune a Transformer-based model (BERT) for multiclass text classification and evaluate its performance using standard NLP metrics.

---

## 📊 Dataset
**AG News Dataset**

- 120,000 training samples
- 7,600 testing samples
- 4 classes:
  - World
  - Sports
  - Business
  - Sci/Tech

Each sample contains:
- Title
- Description
- Label (1–4)

---

## 🛠️ Technologies Used

- Python
- Hugging Face Transformers
- PyTorch
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧠 Model Details

- Model: `bert-base-uncased`
- Fine-tuning approach: Transfer Learning
- Max Sequence Length: 128
- Loss Function: Cross-Entropy
- Optimizer: AdamW

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Loaded CSV dataset
- Cleaned labels
- Combined title + description

### 2. Tokenization
- Used BERT tokenizer
- Applied truncation and padding

### 3. Model Training
- Fine-tuned BERT for 1–2 epochs
- Used Hugging Face Trainer API

### 4. Evaluation
- Accuracy
- F1 Score
- Confusion Matrix

---

## 📈 Results

- Accuracy: ~90%+ (depends on training setup)
- F1 Score: High performance across all classes

---

## 📊 Confusion Matrix
(See notebook for visualization)

---

## 📁 Project Structure
