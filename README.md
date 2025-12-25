# 🚀 Natural Language Processing with Disaster Tweets
This repository contains **Natural Language Processing projects** built with **deep learning language models such as BERT and DistilBERT**.
  
The main projects include:
- **Disaster Tweets Classification** (Kaggle Competition)
- **Sentiment Analysis using NSMC (Naver Sentiment Movie Corpus)**
  
The goal of this repository is to explore **Transformer-based fine-tuning workflows** and compare implementations across **PyTorch and TensorFlow**.
<br/>
<br/>

## 📂 Project Overview
  
### 1️⃣ Disaster Tweets Classification
This project focuses on **binary text classification**, predicting whether a given tweet refers to a **real disaster event** or not.
The dataset comes from Kaggle’s **“Natural Language Processing with Disaster Tweets”** competition.
  
#### 📁 Key Files
- `NLP with Disaster Tweets using DistilBERT-Baseline.ipynb`  
  - PyTorch + Hugging Face Transformers  
  - Baseline DistilBERT fine-tuning pipeline
  
- `KerasNLP_starter_notebook_Disaster_Tweets.ipynb`  
  - TensorFlow + KerasNLP implementation  
  - DistilBERT training and evaluation
  
- `train.csv`, `test.csv`  
  - Training and inference datasets provided by Kaggle
  
#### 🤖 Model
- **DistilBERT** (`distilbert-base-uncased`)
  
#### 📈 Result
- Validation Accuracy: **~0.83** (KerasNLP implementation)
<br/>

### 2️⃣ NSMC Sentiment Analysis
This project performs **sentiment classification (positive / negative)** on the **Naver Sentiment Movie Corpus (NSMC)**.
The same task is implemented using **both PyTorch and TensorFlow** to compare model pipelines, training loops, and framework-specific design choices.
  
#### 📁 Key Files
- `nsmc sentiment analysis/nsmc 감성 분석_파이토치.ipynb`  
  - PyTorch-based implementation
  
- `nsmc sentiment analysis/nsmc 감성 분석 과제_텐서플로우.ipynb`  
  - TensorFlow (Keras) implementation
  
#### 🤖 Model
- **Multilingual BERT** (`bert-base-multilingual-cased`)
  
#### 📊 Dataset
- `nsmc` dataset from the **Hugging Face `datasets` library**
<br/>
<br/>

## 🛠 Tech Stack
  
- **Languages**
  - Python
  
- **Deep Learning Frameworks**
  - PyTorch
  - TensorFlow / Keras
  
- **NLP Libraries**
  - Hugging Face Transformers
  - KerasNLP
  - Datasets
  
- **Data Processing**
  - Pandas
  - NumPy
  - Scikit-learn
  
- **Visualization**
  - Matplotlib
  - Seaborn
<br/>
<br/>

## 🚀 How to Run
All projects are implemented as **Jupyter Notebooks (`.ipynb`)**
- You can run them in:
  - **Google Colab**
  - **Local Jupyter Notebook environments**
  
Each notebook follows the standard NLP workflow:
1. Data loading
2. Preprocessing & tokenization
3. Model fine-tuning
4. Evaluation and analysis
<br/>
<br/>
