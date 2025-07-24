# 😄 Emotion Detection using LSTM (PyTorch NLP)

A natural language processing project using PyTorch and LSTM (Long Short-Term Memory) networks to detect emotions from text data such as tweets or messages.

---

## 📌 Project Overview

Emotion detection is a text classification task that identifies the emotional tone behind a body of text. This project uses an LSTM-based recurrent neural network to classify user messages into emotions such as joy, anger, sadness, fear, etc.

---

## 📁 Project Structure

emotion-detection-lstm/
│
├── data/ # Contains emotion dataset (CSV or TXT)
├── models/ # Trained model weights (.pt files)
├── outputs/ # Evaluation results, predictions
├── train.py # Script to train the model
├── evaluate.py # Script to evaluate model performance
├── preprocess.py # Text cleaning and tokenization
├── utils.py # Utility functions
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## 📊 Dataset

- **Source**: [Emotion Dataset for NLP](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp)
- **Format**: Text + Emotion Label (CSV format)
- **Examples**:

| Text                          | Emotion   |
|------------------------------|-----------|
| "I feel fantastic!"          | joy       |
| "This is so frustrating."    | anger     |
| "I’m feeling really down."   | sadness   |

---

## 🧠 Model Architecture

- **Type**: LSTM-based Recurrent Neural Network
- **Embedding Layer**: Pretrained GloVe (optional)
- **LSTM Layers**: 1-2 stacked layers
- **Dropout**: Used for regularization
- **Output Layer**: Softmax over emotion classes
- **Loss**: CrossEntropyLoss
- **Optimizer**: Adam
- **Metrics**: Accuracy, F1-score

---

## ⚙️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/amantikale/emotion-detection-lstm.git
cd emotion-detection-lstm

pip install -r requirements.txt

python train.py

python evaluate.py

Validation Accuracy: 92.4%
Test Accuracy: 91.3%
F1 Score: 0.91

