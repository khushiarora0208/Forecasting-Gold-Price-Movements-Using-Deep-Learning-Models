# 📈 Forecasting Gold Price Movements Using Deep Learning Models  

## 📌 Overview  
This project builds a **deep learning-based predictive model** for forecasting **gold prices** using historical data and economic indicators such as the **US Dollar Index, Inflation Rate, GDP Growth Rate, and even agricultural commodity prices (Onion Price)**. Multiple deep learning models—including **LSTM, GRU, RNN, and Transformer models**—are evaluated for their predictive accuracy.  

The **LSTM model** outperformed all others, achieving **99.18% accuracy**, demonstrating its effectiveness in handling complex time-series data.  

## 🚀 Features  
- **Multi-Factor Gold Price Prediction**: Considers macroeconomic and agricultural factors.  
- **Deep Learning-Based Models**: Evaluates **LSTM, GRU, RNN, and Transformer** architectures.  
- **High Accuracy Forecasting**: LSTM model achieves **99.18% accuracy** with low error rates.  
- **Data Preprocessing Pipeline**: Handles missing values, outliers, and normalizes data for better model performance.  
- **Ensemble Learning**: Combines multiple model outputs for better stability and accuracy.  

## 🏗️ Tech Stack  
- **Deep Learning Models**: LSTM, GRU, RNN, Transformer  
- **Libraries**: TensorFlow, Keras, NumPy, Pandas, Matplotlib  
- **Dataset Source**: Yahoo Finance (Gold Prices, Economic Indicators), Agmarket (Onion Prices)  
- **Hyperparameter Tuning**: Keras-Tuner  

## 📊 Dataset Description  
- **Time Period**: 2019 - 2024  
- **Total Records**: 2,436 rows  
- **Columns**:  
  - **Date**: Timestamp of record  
  - **Gold Price**: Target variable  
  - **US Dollar Index**: USD strength vs. other currencies  
  - **Inflation Rate**: Percentage inflation in India  
  - **GDP Growth Rate**: Economic performance indicator  
  - **Onion Price**: Agriculture commodity data (potential influence on economic trends)  

## 📉 Model Performance Comparison  
| Model       | MAE  | MAPE (%) | R² Score |  
|------------|------|----------|----------|  
| **LSTM**   | 347.24 | 0.61%  | **0.9918**  |  
| **GRU**    | 596.17 | 1.05%  | 0.9784  |  
| **RNN**    | 4936.67 | 8.09%  | -0.7558  |  
| **Ensemble** | 1765.37 | 2.89%  | 0.7708  |  


## 🎯 Future Enhancements  
- Integrate **real-time gold price updates** for live forecasting.  
- Explore **Transformer-based architectures (e.g., BERT, T5)** for improved performance.  
- Add more **macroeconomic indicators (Interest Rates, Stock Market Data, Crude Oil Prices, etc.)**.  
- Deploy as a **web or mobile application** for user-friendly accessibility.  
