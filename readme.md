# Stock Price Prediction using LSTM and GRU

This project applies deep learning models (LSTM and GRU) to predict future stock prices based on historical data. It leverages neural network architectures designed for time series forecasting.

## 📚 Description

- Downloads historical stock data using `yfinance`.
- Preprocesses data (normalization, reshaping) for deep learning input.
- Trains two models: Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU).
- Compares the prediction results of both models using visualizations and evaluation metrics.

## 🧰 Libraries Used

- NumPy  
- Pandas  
- Matplotlib  
- yfinance  
- scikit-learn  
- TensorFlow / Keras  

## 🛠️ Features

- Interactive input for stock ticker selection.
- Data normalization using MinMaxScaler.
- Construction of LSTM and GRU models with Keras.
- Visualization of predicted vs actual stock prices.
- Evaluation using RMSE.

## 🚀 How to Run

1. Clone this repository.  
2. Install dependencies from \`requirements.txt\`.  
3. Run the notebook using Jupyter.

\`\`\`bash
pip install -r requirements.txt
jupyter notebook "Stock analysis using LSTM and GRU.ipynb"
\`\`\`

## 📁 File Structure

- \`Stock analysis using LSTM and GRU.ipynb\` - Main notebook with all code.  
- \`requirements.txt\` - Python libraries needed for execution.  

## 🔮 Future Enhancements

- Integrate more stocks for batch predictions.  
- Add external features (e.g., sentiment, macroeconomics).  
- Deploy as a forecasting dashboard.  

## 📄 License

This project is licensed under the MIT License.

