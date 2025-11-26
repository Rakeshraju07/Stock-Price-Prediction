# Stock-Price-Prediction
A fully interactive Real-Time Stock Dashboard built using Streamlit, yFinance, and Plotly. This application allows users to monitor live stock prices, visualize market trends, and analyze technical indicators in a simple and intuitive interface
📈 Real-Time Stock Dashboard

A fully interactive Real-Time Stock Dashboard built using Streamlit, yFinance, and Plotly. This application allows users to monitor live stock prices, visualize market trends, and analyze technical indicators in a simple and intuitive interface.

🚀 Features
✅ Real-Time Stock Data

Fetches up-to-date price data using yfinance

Supports multiple time periods: 1d, 1wk, 1mo, 1y, max

Automatically adjusts interval depending on the time period selected

📊 Interactive Charts

Candlestick chart for visualizing price movements

Additional line chart option

Dynamic Plotly graphs with zoom & hover support

📉 Technical Indicators

Includes commonly used indicators:

SMA 20 (Simple Moving Average)

EMA 20 (Exponential Moving Average)
Selectable via sidebar

📁 Historical Data View

Complete dataset displayed in table format

Includes OHLC prices and volume

Separate section for technical indicators

📦 Sidebar Real-Time Stock Prices

Shows quick metrics for popular stocks:

AAPL

GOOGL

AMZN

MSFT

🧭 Simple & Clean UI

Easy-to-use Streamlit sidebar controls

Metrics for last price, price change, % change, high, low, and volume

Auto timezone conversion to US/Eastern

🛠 Technology Stack

Python

Streamlit (UI)

Plotly (Interactive charts)

yFinance (Real-time stock market data)

Pandas

TA (Technical Analysis library)

📦 How to Run the App
pip install -r requirements.txt
streamlit run app.py

📥 Project Structure (example)
.
├── app.py
├── requirements.txt
└── README.md

🎯 Purpose of the Project

This project showcases:

Real-time data processing

Financial data visualization

Technical indicator analysis

Interactive dashboard development

API integration and data engineering skills

Perfect for finance enthusiasts, students, data analysts, or developers exploring fintech tools.
