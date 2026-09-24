# 📰 News Categorization using BERT (NEWSBERT)

A deep learning–based news classification system using **BERT (Bidirectional Encoder Representations from Transformers)** to automatically categorize news articles into multiple categories such as business, politics, sports, entertainment, and technology.

This project demonstrates how transformer-based NLP models can efficiently classify large volumes of digital news content with high accuracy.

---

## 📌 Project Overview
With the rapid growth of online news content, manual categorization has become inefficient and error-prone.  
This project implements a **BERT-based deep learning model** that automatically classifies news articles into predefined categories using natural language processing techniques.

The system is trained on the **BBC News dataset** and achieves high classification accuracy with strong generalization on unseen data. :contentReference[oaicite:0]{index=0}  

---

## 🎯 Objectives
- Build an automated news classification system  
- Use BERT for contextual text understanding  
- Classify news into 5 categories:
  - Business  
  - Entertainment  
  - Politics  
  - Sports  
  - Technology  
- Achieve high accuracy and robust performance  
- Enable real-time prediction on new news text  

---

## 🛠 Tech Stack
- Python  
- BERT (Transformers - HuggingFace)  
- PyTorch  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📂 Dataset
**BBC News Dataset**
- ~2200 news articles  
- 5 categories: business, entertainment, politics, sport, tech  
- Balanced dataset suitable for multi-class classification :contentReference[oaicite:1]{index=1}  

---

## 🧪 Methodology
### Data Preprocessing
- Text cleaning & normalization  
- Tokenization using BERT tokenizer  
- Label encoding  
- Train-test split (80/20)

### Model Architecture
- Pretrained BERT (bert-base-uncased)  
- Added classification head  
- Fine-tuned on BBC dataset  

### Training Configuration
- Optimizer: AdamW  
- Learning rate: 2e-5  
- Batch size: 8  
- Epochs: 3  
- Loss: Cross entropy  

---

## 📊 Results
- **Test Accuracy:** 96.85%  
- High precision, recall, and F1-score across all classes  
- Strong performance compared to traditional ML models  

BERT significantly outperformed baseline models like SVM, CNN, and LSTM for news classification tasks. :contentReference[oaicite:2]{index=2}  

---

## 🚀 Features
- Multi-class news classification  
- Transformer-based NLP model  
- High accuracy and generalization  
- Real-time prediction capability  
- Scalable for real-world deployment  

---

## 🌍 Applications
- Automated news categorization systems  
- News recommendation engines  
- Content filtering platforms  
- Fake news detection systems  
- Media analytics and monitoring  

---

## 🔮 Future Improvements
- Hyperparameter tuning & optimization  
- Multilingual news classification  
- Real-time API integration  
- Deployment as web application  
- Fake news detection integration  

---

## 👩‍💻 Author
**Megha**  
B.Tech CSE (AI & ML)  
RV University, Bangalore  
