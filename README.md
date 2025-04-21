Equity Explorer – Interactive Stock Performance Dashboard

A simple interactive finance app built in Jupyter Notebook using yfinance, pandas, matplotlib, and ipywidgets. Users can select stock tickers and a start year to view normalized total return charts and export the data to CSV/Excel.

🚀 Features

📈 Compare multiple stock tickers

🎚️ Choose custom start year (e.g. 2010–2024)

🧮 Calculates CAGR (Compound Annual Growth Rate)

📊 Interactive matplotlib plot (normalized to 100)

💾 Export to CSV or Excel

✅ Output area updates dynamically with each run

🧠 Technologies Used

Tool

Purpose

yfinance

Stock data API

pandas

Data manipulation

matplotlib

Plotting performance graphs

ipywidgets

Interactive UI (text, sliders, buttons)

Jupyter Notebook

Interactive development environment

📂 Repository Structure

fintech-dashboard/
├── Equity_Explorer.ipynb        # Main notebook
├── stock_returns_2016.csv       # Example export file (optional)
├── README.md                    # Project overview
├── .gitignore                   # Ignore data files and system clutter

▶️ How to Run

Open Equity_Explorer.ipynb in Jupyter Notebook

Run the first 3 cells (widget setup, analysis function, button wiring)

Select tickers and start year

Click “↑ Run Analysis”

Click “📅 Export” to download data in your preferred format

🖼 Screenshot

Add screenshot or Loom link showing the widget dashboard and plot

✅ Tips

No API key needed (uses yfinance)

Make sure to install dependencies with:

pip install yfinance matplotlib pandas ipywidgets openpyxl

If widgets don’t show: run in classic Jupyter Notebook and follow ipywidgets install instructions

📄 License

MIT License — free to use, modify, and share.
