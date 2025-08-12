# SurfTrend


-Built SurfTrend, a Python relative-strength (RS) framework for Indian equities: automated data ingestion (yfinance, NSE jugaad), computed weekly / monthly / quarterly sector-relative returns vs NIFTY, ranked stocks by an RS score, and produced trade-ready allocations with live quotes and position sizing (Pandas/NumPy).
-Shipped an interactive Streamlit dashboard backed by SQLite + SQLAlchemy: cached OHLCV & sector equity curves, and exposed Top RS Stocks, Sectors Analysis, and Sector Indices views; modularized the pipeline (return_analysis, nifty_ret, stocks_selector) for reproducible research and easy extension.
