# 📰 News Categorization using BERT (NEWSBERT)

A deep learning-based **news classification system using BERT (Bidirectional Encoder Representations from Transformers)** to automatically categorize news articles into five categories: **Business, Entertainment, Politics, Sports, and Technology**.

This project demonstrates the use of transformer-based Natural Language Processing (NLP) for accurate and automated news classification.

---

## 📌 Project Overview

With the rapid growth of online news content, manually categorizing large volumes of news articles can be inefficient and error-prone.

**NEWSBERT** addresses this problem by using a pretrained **BERT model** fine-tuned on the **BBC News dataset** to automatically classify news articles into predefined categories.

The model is trained to understand the contextual meaning of news text and predict the appropriate category for previously unseen articles.

---

## 🎯 Objectives

* Build an automated news classification system
* Apply BERT for contextual understanding of text
* Classify news articles into five categories:

  * 💼 Business
  * 🎬 Entertainment
  * 🏛️ Politics
  * ⚽ Sports
  * 💻 Technology
* Achieve high classification accuracy and robust performance
* Enable prediction of categories for new news articles

---

## 🛠️ Tech Stack

| Technology                    | Purpose                                |
| ----------------------------- | -------------------------------------- |
| **Python**                    | Core programming language              |
| **BERT**                      | Text representation and classification |
| **Hugging Face Transformers** | BERT implementation and tokenization   |
| **PyTorch**                   | Deep learning framework                |
| **Pandas & NumPy**            | Data processing and manipulation       |
| **Scikit-learn**              | Data splitting and evaluation          |
| **Matplotlib & Seaborn**      | Data visualization                     |

---

## 📂 Dataset

### BBC News Dataset

The project uses the **BBC News dataset**, containing approximately **2,200 news articles** across five categories:

* Business
* Entertainment
* Politics
* Sport
* Technology

The dataset provides a suitable multi-class classification problem for evaluating transformer-based NLP models.

---

## 🔄 Methodology

### 1. Data Preprocessing

* Load and inspect the BBC News dataset
* Clean and normalize the text
* Encode category labels
* Split the dataset into training and testing sets using an **80/20 split**

### 2. BERT Tokenization

The text is tokenized using the pretrained **BERT tokenizer**, converting the news articles into token IDs and attention masks suitable for the BERT model.

### 3. Model Architecture

The project uses:

* **Pretrained `bert-base-uncased`**
* A classification head added on top of BERT
* Fine-tuning of the model on the BBC News dataset

### 4. Model Training

The training configuration includes:

* **Optimizer:** AdamW
* **Learning Rate:** 2e-5
* **Batch Size:** 8
* **Epochs:** 3
* **Loss Function:** Cross Entropy Loss

### 5. Evaluation

The trained model is evaluated on unseen test data using classification performance metrics such as:

* Accuracy
* Precision
* Recall
* F1-score

---

## 📊 Results

The trained BERT model achieved:

> **Test Accuracy: 96.85%**

The model demonstrated strong classification performance across the five news categories, with high precision, recall, and F1-score.

---

## 🚀 Features

* Multi-class news classification
* BERT-based contextual text understanding
* Fine-tuning of a pretrained transformer model
* Classification across five news categories
* Prediction of categories for new news articles
* High classification accuracy

---

## 📁 Project Structure

```text
news-categorization/
│
├── README.md
├── Newsbert.ipynb
├── Newsbert_train.ipynb
├── grid_search.ipynb
└── bbc-text.csv
```

### Notebooks

**`Newsbert_train.ipynb`**
Contains the training and fine-tuning process for the BERT-based classification model.

**`Newsbert.ipynb`**
Contains the main BERT-based news categorization workflow and prediction process.

**`grid_search.ipynb`**
Contains hyperparameter tuning and experimentation.

**`bbc-text.csv`**
Dataset containing the news articles and their corresponding categories.

---

## 🌍 Applications

The approach can be used in applications such as:

* Automated news categorization
* News recommendation systems
* Content filtering platforms
* Media analytics and monitoring
* Large-scale news content organization

---

## 🔮 Future Improvements

* Further hyperparameter tuning and optimization
* Multilingual news classification
* Real-time API integration
* Deployment as a web application
* Extension toward related NLP tasks such as fake-news detection

---

## 👩‍💻 Author

**Prakruthi S**
B.Tech Honours in Computer Science and Engineering
**Specialization:** Data Science and Engineering
RV University, Bangalore





