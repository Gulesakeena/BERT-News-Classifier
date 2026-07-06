# 📰 News Topic Classification using BERT

## 📌 Project Overview

This project is part of the **DevelopersHub Corporation AI/ML Engineering Internship (Advanced Task 1)**.

The goal is to build a **news topic classification system** using a fine-tuned **BERT (bert-base-uncased)** transformer model. The model classifies news articles into four categories:

- 🌍 World  
- 🏅 Sports  
- 💼 Business  
- 🔬 Sci/Tech  

The project demonstrates the use of **Transfer Learning with Transformers** for real-world NLP classification tasks.

---

## 🎯 Objective

- Fine-tune a pre-trained BERT model on the AG News dataset  
- Classify news articles into 4 categories  
- Evaluate model performance using accuracy and F1-score  
- Generate predictions for unseen test data  
- Visualize performance using confusion matrix  

---

## 📊 Dataset Information

**Dataset:** AG News Classification Dataset  

- 120,000 training samples  
- 7,600 test samples  
- 4 classes:
  - 1 → World
  - 2 → Sports
  - 3 → Business
  - 4 → Sci/Tech  

Each sample contains:
- Title
- Description
- Label

---

## 🛠️ Technologies Used

- Python 🐍  
- Hugging Face Transformers 🤗  
- PyTorch 🔥  
- Scikit-learn 📊  
- Pandas & NumPy  
- Matplotlib & Seaborn  

---

## 🧠 Model Details

- Model: `bert-base-uncased`
- Task: Text Classification
- Approach: Fine-tuning (Transfer Learning)
- Max Sequence Length: 128 tokens
- Loss Function: Cross-Entropy Loss
- Optimizer: AdamW
- Framework: Hugging Face Trainer API

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing
- Loaded AG News dataset (CSV format)
- Cleaned labels and removed invalid rows
- Combined title and description into a single text field

### 2️⃣ Tokenization
- Used BERT tokenizer
- Applied truncation and padding
- Converted text into input IDs and attention masks

### 3️⃣ Model Training
- Fine-tuned BERT on training dataset
- Used Hugging Face Trainer API
- Evaluated using validation dataset

### 4️⃣ Evaluation
- Accuracy Score
- F1 Score (Weighted)
- Confusion Matrix

---

## 📈 Results

The fine-tuned model achieved strong performance on the AG News dataset:

- ✅ Accuracy: ~90%+ (varies based on training setup)
- ✅ F1 Score: High weighted performance across all classes

---

## 📊 Confusion Matrix

The confusion matrix shows strong classification performance across all four categories, with minor misclassifications between similar topics.

*(See notebook for visualization)*

---

## 📁 Project Structure
