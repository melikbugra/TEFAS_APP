# TEFAS Funds Analysis & Portfolio Management Tool

This is a web-based application built with [Streamlit](https://streamlit.io/) for analyzing TEFAS funds and managing investment portfolios. The application allows users to visualize fund data, track transactions, and calculate gains, providing insights into portfolio performance.

## 🎯 Features

- **Data Extraction**: 
  - Extract price, investor count, fund amount data from TEFAS.gov.tr 

- **Fund Analysis**: 
  - Displays TEFAS fund data, including historical prices and performance indicators.
  - Integrated with locally downloaded `tefas_transformed.csv` to visualize fund unit prices.

- **Portfolio Management**:
  - Manage buy/sell transactions with a user-friendly interface.
  - Automatically calculates portfolio statistics such as quantity, cost and revenue basis, and yearly gains.
  - Saves portfolio data locally as `myportfolio.csv`.

- **Data Visualization**:
  - Summary tables with performance metrics.
  - Graphical analysis of fund performance over time.

## 🛠 Technologies Used

- **Streamlit**: For building the web interface.
- **Pandas**: For data manipulation and analysis.
- **CSV Files**: Stores transaction and fund data (`myportfolio.csv`, `tefas_transformed.csv`).

## 🚀 Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/ozturkergin/TEFAS_APP.git
    ```

2. Run the Streamlit app:
    ```bash
    execute run.bat 
    ```
    This will automatically execute requirement installation for python libraries. pip install -r requirements.txt

## 💼 Usage

- **Portfolio Transactions**: Add new transactions (buy/sell) via the form in the app. Data is stored and recalculated dynamically.
- **Fund Analysis**: View historical data and performance for TEFAS funds.
- **Save Portfolio**: Ensure data persistence by clicking the **Save** button after entering new transactions.

## 📜 License

This project is licensed under the MIT License.


