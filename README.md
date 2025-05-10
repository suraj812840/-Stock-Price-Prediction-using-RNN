# -Stock-Price-Prediction-using-RNN
This project focuses on predicting future stock prices using Recurrent Neural Networks (RNN). We use historical stock data for training and evaluate the model on unseen data to assess its performance.

# 📈 Stock Price Prediction using RNN

This project focuses on predicting future stock prices using Recurrent Neural Networks (RNN). We use historical stock data for training and evaluate the model on unseen data to assess its performance.

## 📂 Dataset

The dataset contains historical stock prices with the following columns:
- `Date`
- `Open`
- `High`
- `Low`
- `Close`
- `Adj Close`
- `Volume`

> Data Range: From **2010-06-29** to **2022-03-24**  
> Total Rows: **2956**

### Sample Data

| Date       | Open     | High     | Low      | Close    | Adj Close | Volume   |
|------------|----------|----------|----------|----------|-----------|----------|
| 2010-06-29 | 3.80     | 5.00     | 3.51     | 4.78     | 4.78      | 93831500 |
| 2022-03-24 | 1009.73  | 1024.49  | 988.80   | 1013.92  | 1013.92   | 22901900 |

## ⚙️ Technologies Used

- Python 🐍
- Numpy, Pandas
- Matplotlib, Seaborn
- TensorFlow / Keras
- Scikit-learn

## 🔁 RNN Model Architecture

- Input: Sequential stock price data
- Layers:
  - SimpleRNN / LSTM
  - Dense output layer
- Loss: Mean Squared Error (MSE)
- Optimizer: Adam

## 📊 Evaluation

- Metrics: MSE, RMSE
- Visuals: Line plot comparing actual vs predicted stock prices

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/stock-price-prediction-rnn.git
cd stock-price-prediction-rnn
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook or script:
```bash
python rnn_stock_predict.py
# OR open RNN_Stock_Prediction.ipynb in Jupyter
```

## 📁 File Structure

```
├── data/
│   └── stock_data.csv
├── rnn_stock_predict.py
├── RNN_Stock_Prediction.ipynb
├── requirements.txt
└── README.md
```

## 🧠 Future Work

- Try LSTM/GRU for improved accuracy
- Predict multiple future time steps
- Build a Streamlit dashboard for real-time prediction

## 📬 Contact

For queries, reach out to: **surajsingh81284026@gmail.com**
