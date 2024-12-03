# Kraken Trading Pairs Lists (CC BY 4.0)

https://www.kraken.com/

## Overview

Welcome to the **Kraken Trading Pairs Lists** repository! This repository contains curated lists of trading pairs available on the **Kraken** cryptocurrency exchange, formatted for easy import into platforms like **TradingView**.

### **Contents:**

- **Crypto pairings:** Trading pairs where **BTC** (Bitcoin) is the main quote currency.
- **USDT pairings:** Trading pairs where **USDT** (Tether) is the main quote currency.
- **Various combined pairings:** A comprehensive list combining both BTC, USDT and Fiat pairings.

## Data Source

All trading pairs listed here are accurate as of **December 3rd, 2024**, based on data from Kraken's [Supported Trading Pairs](https://support.kraken.com/hc/en-us/articles/kraken-markets) page.

## License

This project is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE). You are free to share and adapt the material for any purpose, even commercially, as long as you provide appropriate credit.

## Repository Structure
- **CODE_OF_CONDUCT.md**
- **CONTRIBUTING.md**
- **LICENSE**
- **README.md**
- **tv_BTC_Pairings.txt:** Contains all trading pairs with BTC as the quote currency.
- **tv_Combined_Crypto-Crypto_Pairings:** A merged list of both BTC and USDT trading pairs.
- **tv_Combined_Crypto-Fiat_Pairings:** A merger list of Crypto and Fiat trading pairs.
- **tv_USDT_Pairings.txt:** Contains all trading pairs with USDT as the quote currency.

## How to Use

### **Importing into TradingView**

#### **Method 1: Using the Watchlist Import Feature**

1. **Open TradingView:**
   - Navigate to [TradingView](https://www.tradingview.com/) and log in to your account.

2. **Access the Watchlist Panel:**
   - Locate the **Watchlist** panel on the right-hand side. If it's not visible, click on the **"Watchlist"** tab or use the shortcut **`Alt + W`**.

3. **Create a New Watchlist (Optional):**
   - Click the **"+"** icon next to your existing watchlists to create a new one (e.g., "Kraken BTC Pairings", "Kraken USDT Pairings", "Kraken BTC & USDT Pairings").

4. **Import Trading Pairs:**
   - Click on the **"…"** (ellipsis) icon in the desired watchlist panel.
   - Select **"Import list of symbols"** from the dropdown menu.

5. **Paste the Formatted List:**
   - Open the respective `.txt` file from this repository.
   - Copy the entire list.
   - Paste it into TradingView's import prompt.
   - Click **"Import"** to add the symbols to your watchlist.

#### **Method 2: Using a CSV File**

1. **Create a CSV File:**
   - Open a text editor (e.g., Notepad) or spreadsheet software (e.g., Excel, Google Sheets).
   - Enter each trading pair on a new line.

   **Example (`tv_BTC_Pairings.txt`):**
```
KRAKEN:ZRXBTC KRAKEN:AAVEBTC KRAKEN:ALGOBTC KRAKEN:ANKRBTC KRAKEN:BCHBTC KRAKEN:ADABTC KRAKEN:LINKBTC KRAKEN:COMPBTC KRAKEN:ATOMBTC KRAKEN:MANABTC KRAKEN:DOGEBTC KRAKEN:MLNBTC KRAKEN:ETHBTC KRAKEN:ETCBTC KRAKEN:FILBTC KRAKEN:LTCBTC KRAKEN:MKRBTC KRAKEN:MINABTC KRAKEN:XMRBTC KRAKEN:PAXGBTC KRAKEN:DOTBTC KRAKEN:MATICBTC KRAKEN:XRPBTC KRAKEN:SANDBTC KRAKEN:GRTBTC KRAKEN:SNXBTC KRAKEN:SOLBTC KRAKEN:TRXBTC KRAKEN:UNIBTC KRAKEN:WBTCBTC KRAKEN:ZECBTC
```

2. **Import into TradingView:**
- Follow **Method 1** above, but instead of pasting, copy the content from your `.txt` file and paste it into the **"Import list of symbols"** prompt.

### **Example: Importing BTC Pairings**

1. Open `tv_BTC_Pairings.txt`.
2. Copy the entire list.
3. Paste it into TradingView's **"Import list of symbols"** prompt.
4. Click **"Import"**.

## Contributing

Contributions are welcome! If you find any discrepancies or have suggestions for additional trading pairs, feel free to open an issue or submit a pull request.

### **How to Contribute:**

1. **Fork the Repository.**
2. **Create a New Branch:**
```bash
git checkout -b feature/add-new-pair
```

3. **Make Your Changes.**
4. **Commit Your Changes:**
```bash
git commit -m "Add new trading pair for XYZ"
```

5. **Push to the Branch:**
```bash
git push origin feature/add-new-pair
```

6. **Open a Pull Request.**

## Disclaimer
The trading pairs listed in this repository are accurate as of December 3rd, 2024. Cryptocurrency markets are highly volatile, and trading pairs may change over time. Always verify the availability of trading pairs directly on Kraken's official platform before making any trading decisions.

## Contact
For any questions or feedback, please reach out via GitHub Issues.

![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)
