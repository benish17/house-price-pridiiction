# 🧠 house Price Prediction

This project uses **machine learning** to predict the next day's stock closing price using historical stock data.

---

## 📊 Features

- Fetches historical stock data using `yfinance`
- Prepares and cleans the dataset
- Uses `LinearRegression` model from `scikit-learn`
- Evaluates model with metrics: RMSE, R² score
- Visualizes actual vs predicted prices using `matplotlib`

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- yfinance

---

## 🧪 How It Works

1. Downloads stock data (e.g. Apple) from 2020 to 2024
2. Shifts the closing price by 1 day to set up the prediction target
3. Trains the model to predict future close prices based on:
   - Open
   - High
   - Low
   - Volume

---

## 📈 Model Evaluation

- **RMSE (Root Mean Squared Error)**: Measures how far predictions are from real prices
- **R² Score**: Explains how much variance is captured by the model

---

## 🖼️ Output Example

![Prediction Graph](example.png)

---

## 📂 Folder Structure

📦Stock-Price-Prediction/
├── stock_prediction.ipynb
├── housing.csv (if needed)
├── README.md


---

## 🚀 How to Run

```bash
pip install yfinance pandas matplotlib seaborn scikit-learn


---

Let me know if you want it customized with your **name**, **GitHub username**, or **screenshot** of your output!
