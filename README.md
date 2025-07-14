# 🔋 Battery IoT (SQL + Python) Analysis

This project explores and visualizes data from a battery testing database using **SQLite**, **Pandas**, and **Matplotlib** in a Jupyter Notebook environment (Anaconda). The database includes information about battery cells, test sessions, and detailed time-series voltage, current, and temperature readings.

## 📁 Dataset

- **File**: `battery.sqlite`
- **Tables**:
  - `Celula`: Battery cell information
  - `Teste`: Metadata for each test (date, type, temperature)
  - `Valor_Teste`: Time-series data including voltage, current, and temperature
  - `sqlite_sequence`: Internal SQLite table (ignored)

## 🔍 Key Insights

1. Number of cells by chemistry type
2. Average temperature by test type
3. Voltage and current over time for a specific test
4. Temperature evolution over time
5. Number of tests per chemistry type
6. Voltage statistics (max, min, avg) per test
7. Average power per test
8. Monthly test trends

📊 Example Output
Bar plots for test counts and chemistry types

Line charts for voltage/current/time series

Monthly trends for test activity

📦 Tools Used
Python

SQLite

Pandas

Matplotlib

Jupyter Notebook (Anaconda)
