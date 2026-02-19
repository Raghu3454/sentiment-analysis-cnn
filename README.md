# 🧠 CNN-Based Sentiment Analysis

## 📌 Project Overview

This project implements Sentiment Analysis using a Convolutional Neural Network (CNN) to classify movie reviews as Positive or Negative.

The model is trained on the IMDB movie review dataset and achieves high classification accuracy.

This project was developed as part of an AI & Data Science internship task.

---

## 🧠 About Sentiment Analysis

Sentiment Analysis is a Natural Language Processing (NLP) task that determines whether a given text expresses a positive or negative opinion.

In this project, a Convolutional Neural Network (CNN) is used for text classification.

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- Numpy
- Matplotlib
- Google Colab

---

## 📂 Dataset

IMDB Movie Review Dataset

- 25,000 training samples
- 25,000 testing samples
- Binary classification (Positive / Negative)

Only the top 5000 most frequent words were used for training.

---

## ⚙️ Model Architecture

The CNN model consists of:

1. Embedding Layer  
2. Conv1D Layer  
3. Global Max Pooling Layer  
4. Dense Layer  
5. Dropout Layer  
6. Output Layer (Sigmoid Activation)

Binary Crossentropy loss and Adam optimizer were used for training.

---

## 📊 Results

- Achieved approximately 85–90% test accuracy.
- Validation accuracy closely matched training accuracy.
- Model successfully classifies unseen reviews.

(Add screenshot of accuracy graph here)

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Enable GPU (Runtime → Change runtime type → GPU)
3. Run all cells
4. View training and evaluation results

---

## 📈 Future Improvements

- Increase vocabulary size
- Add LSTM/GRU comparison
- Hyperparameter tuning
- Deploy as web application
- Use custom text dataset

---

## 👨‍💻 Author

Raghavendra  
B.Tech - Artificial Intelligence & Data Science  
Aspiring AI & Machine Learning Engineer
