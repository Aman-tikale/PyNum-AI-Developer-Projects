# 🏠 House Price Prediction using PyTorch (Tabular Regression)

A machine learning project that uses PyTorch and Fully Connected Neural Networks to predict house prices from structured tabular data.

---

## 📌 Project Overview

This project tackles a supervised regression problem using structured (tabular) data. We use a neural network to learn from features like number of rooms, location, area, year built, etc., and predict the sale price of a house.

---

## 📁 Project Structure

# Placeholder for README.md

---

## 📊 Dataset

- **Source**: [Kaggle: House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- **Samples**: 1,460 rows
- **Features**: 80 (categorical + numeric)
- **Target**: `SalePrice` (continuous variable)

---

## 🧠 Model Architecture

- **Type**: Feedforward Fully Connected Neural Network (FCNN)
- **Layers**: Input → Hidden (ReLU) → Hidden (ReLU) → Output
- **Loss Function**: Mean Squared Error (MSELoss)
- **Optimizer**: Adam
- **Evaluation Metrics**: RMSE, MAE, R² Score

---

## ⚙️ How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/amantikale/house-price-prediction.git
cd house-price-prediction


2. Install Required Libraries
bash
Copy
Edit
pip install -r requirements.txt
3. Train the Model
bash
Copy
Edit
python train.py
4. Evaluate the Model
bash
Copy
Edit
python evaluate.py
📈 Sample Results
javascript
Copy
Edit
Actual Price: $248,000
Predicted Price: $243,500

Mean Absolute Error: $4,500
Root Mean Squared Error: $5,300
R² Score: 0.91

