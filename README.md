<p align="center">
    <img src="stock.png" width="80" alt="Stock Price Predictor Logo"/>
</p>

# 📈 Stock Price Predictor

Predict tomorrow’s stock closing price using historical data and today’s news sentiment! 🚀

---

## ✨ Features

- 📊 Predicts stock closing prices using LSTM and news sentiment analysis
- 📰 Integrates real-time news sentiment for better accuracy
- 📈 Uses moving averages and multiple stock strategies
- 🔎 Data collected via Yahoo web scraping

---

## 🚀 Quick Start

### 1. Download Model Files

Download the model and tokenizer folders from [Google Drive](https://drive.google.com/drive/folders/1PPKOWUygpNf9HfECWR1wLgiKwNWMGFPx?usp=sharing) and place them in the `backend/` folder.

### 2. Frontend Setup

```bash
cd frontend
npm i --force
npm start
```

### 3. Backend Setup

```bash
cd backend
python -m venv env
# On Linux
source env/bin/activate
# On Windows
env/Scripts/activate
pip install -r requirements.txt
python server.py
```

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Firebase
- **Backend:** Python (Flask), LSTM, Sentiment Analysis
- **Data:** Yahoo Finance, News APIs

---

## 📸 Screenshots

<!-- Add screenshots here -->
<p align="center">
    <img src="https://via.placeholder.com/600x300?text=Dashboard+Screenshot" width="70%"/>
</p>

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License.
