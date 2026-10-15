# 🤖 Automated Live Crypto Financial Pipeline

An automated data engineering script that pings live REST APIs, structures financial JSON payloads into clean Pandas DataFrames, and schedules localized Excel reporting assets.

## ⚙️ Key Features
* **Live Ingestion:** Connects to the public CoinGecko API without needing authentication tokens.
* **Robust Error Handling:** Emulates a standard browser header to bypass server rate-limiting blocks, backed by an immediate static data fallback matrix to guarantee pipeline reliability.
* **Automated Reporting:** Packages and sorts financial data tables into permanent, timestamped Excel spreadsheets dynamically.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Libraries:** Requests, Pandas, OpenPyXL
* **Environment:** Virtual Environments (`venv`) on macOS
