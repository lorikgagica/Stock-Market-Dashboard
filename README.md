# 📈 Stock Market Dashboard (Tkinter + matplotlib)

A beginner-friendly desktop application to visualize stock price histories from CSV files using Python, Tkinter, pandas, and matplotlib. Instantly plot price charts for preselected stocks!

---

## ✨ Features

- **CSV stock data loading:** Reads prices for multiple stocks and dates
- **Dropdown menu**: Choose between available stocks (AAPL, MSFT, etc.)
- **Dynamic charting:** Plots price vs. date for selected stock
- **Modern Tkinter interface**: Responsive, easy to use
- **Matplotlib integration** for interactive and clear visualizations

---

## 🚀 How to Run

1. **Python 3 required**
2. **Install libraries:**
    ```
    pip install pandas matplotlib
    ```
3. **Make sure `stock.py` and `stock_data.csv` are in the same folder**
4. **Run in terminal:**
    ```
    python stock.py
    ```
5. **Select a stock from the dropdown and click "Plot Stock Data"**

---

## 🗂️ Data Format

The `stock_data.csv` should look like this:

| date       | stock | price |
|------------|-------|-------|
| 2025-01-01 | AAPL  | 145   |
| 2025-01-02 | AAPL  | 150   |
| 2025-01-03 | AAPL  | 147   |
| 2025-01-01 | MSFT  | 240   |
| 2025-01-02 | MSFT  | 235   |
| 2025-01-03 | MSFT  | 243   |

Edit/add stocks and dates as needed to fit your dataset.

---

## 🧑‍💻 Usage

- Choose a stock from the dropdown (AAPL/MSFT etc)
- Click **Plot Stock Data**
- See price curve for that stock and timeframe
- Change stock at any time for instant replot

---

## 📄 License

MIT License — free for learning, teaching, and tinkering.

---

A perfect starter for finance, data science, and Python GUI learning!
