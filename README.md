
# 💳 Credit Card Fraud Detection App

This is a **Streamlit web application** that detects credit card fraud using a **Logistic Regression** model trained on the popular `creditcard.csv` dataset. It allows users to input transaction features and returns whether the transaction is **legitimate or fraudulent**.

---

## 🚀 Features

- Built with **Python**, **Streamlit**, and **scikit-learn**
- Input 30 features and get instant prediction
- Balanced dataset using under-sampling
- Logistic Regression model trained and evaluated

---

## 📁 Project Structure

```
Credit card fraud detection project/
│
├── creditcard.csv                     # Dataset
├── Credit Card Fraud Detection.ipynb # Model training notebook
├── app.py                            # Streamlit web app
├── README.md                         # Project documentation
└── .venv/                            # Virtual environment (optional)
```

---

## 📦 Installation

1. **Clone this repository** (or download the folder):

```bash
git clone https://github.com/RitvikSharmaa/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

2. **Create and activate virtual environment** (optional but recommended):

```bash
python -m venv .venv
.venv\Scripts\activate  # On Windows
```

3. **Install dependencies**:

```bash
pip install -r requirements.txt
```

> If you don’t have `requirements.txt`, run:
```bash
pip install streamlit pandas scikit-learn
```

---

## 🧠 How It Works

- Loads `creditcard.csv`
- Balances the dataset (equal number of fraud & legitimate)
- Trains a **Logistic Regression** model
- Takes 30 numerical features as input
- Predicts if transaction is **Legit** or **Fraudulent**

---

## ▶️ Run the App

```bash
streamlit run app.py
```


## 📊 Dataset Info

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Features: 30 anonymized numerical values
- Target: `Class` (0 = Legit, 1 = Fraud)

---

## 📌 To Do

- [ ] Add model saving/loading with joblib
- [ ] Add download button for predictions
- [ ] Improve input form (sliders or number inputs)

---


## 🙋‍♂️ Author

Made by **Ritvik Sharma**

[GitHub](https://github.com/RitvikSharmaa) | 
