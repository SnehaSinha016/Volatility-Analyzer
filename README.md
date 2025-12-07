
# Volatility Analyzer (Google Colab Project)

This project calculates and visualizes the **annualized volatility** of a stock using real historical market data.  
It was developed entirely in **Google Colab**, making it easy to run without installing anything locally.

Volatility is a key concept used in **Sales & Trading, Quant Finance, and Risk Management**.  
This project demonstrates how to use Python to measure market risk in a simple and intuitive way.

---

##  Features

### ✔ Real stock data from Yahoo Finance  
Uses the `yfinance` library to fetch **1-year closing prices** for any stock (NSE, BSE, NYSE, NASDAQ).

### ✔ Calculate important financial metrics  
- **Daily returns**  
- **Annualized volatility** (std × √252)  
- **Rolling volatility (20-day)**  

### ✔ Visualizations included  
- 1-Year Price Chart  
- Rolling Volatility Chart  

### ✔ Interpretation of market risk  
The program classifies volatility as:
-  High  
-  Moderate  
-  Low  

Very similar to how trading desks interpret market risk.

---

##  Run This Project in Google Colab

You can run this project instantly in Google Colab without installing Python.

Click the badge below (if you add one):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

Or manually:

1. Open **Google Colab**  
2. Click **File → Upload Notebook**  
3. Select the `.ipynb` file  
4. Run all cells  

That's it!

---

##  Dependencies (Automatically Installed in Colab)

Google Colab already includes:

- Python  
- pandas  
- numpy  
- matplotlib  

The only extra library needed is:

```python
!pip install yfinance

Volatility-Analyzer/
│── Untitled2.ipynb   # Main Colab notebook
│── README.md                   # Documentation




