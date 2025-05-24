# 🧠📊 Natural Gas Sentiment & Price Predictor

This Streamlit app predicts **natural gas prices** based on **news article sentiment** using a combination of rule-based sentiment detection and machine learning models. It is designed for use by analysts, traders, and researchers to better understand market sentiment around supply and demand factors.

---

## 🚀 Live Demo

👉 [Launch the app](https://pqmhukze64nscptlnzpcyz.streamlit.app/)  
*(Accessible on any browser. No installation needed.)*

---

## ✨ Features

- Accepts any natural gas–related news article text and publication date  
- Extracts **supply** and **demand** sentiment using keyword-based logic  
- Predicts **overall sentiment** using Logistic Regression  
- Predicts **natural gas price** using Random Forest Regressor  
- Retrieves historical price data using financial APIs  
- Provides actionable **investment advice** (buy/wait) based on sentiment and predicted price  

---

## 🛠️ Tech Stack

**Python, NLP, Scikit-learn, Streamlit, TF-IDF, Logistic Regression, Random Forest**

---


## 🔧 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/yourusername/natural-gas-sentiment-predictor.git
cd natural-gas-sentiment-predictor

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```
🧠 Model Overview
Sentiment Classification
Inputs: TF-IDF from article + one-hot supply/demand sentiment

Model: Logistic Regression

Price Prediction
Inputs: TF-IDF + final sentiment

Model: Random Forest Regressor

Keyword-based sentiment scores are computed using domain-specific dictionaries

📊 Future Enhancements
Add real-time news scraping from sources like NewsAPI or Google News

Upgrade models using sentiment embeddings (e.g., BERT, FinBERT)

Expand support to other energy commodities and global market analysis

