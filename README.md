# Global Cryptocurrency Stats Fetcher

This Python script fetches and displays global cryptocurrency statistics from the Coinlore API.

---

## Overview

The script retrieves global cryptocurrency data such as:
- Total number of coins
- Active markets
- Total market capitalization
- 24-hour trading volume
- Dominance of Bitcoin and Ethereum
- Market cap and volume changes over 24 hours
- All-time high market cap and trading volume

The data is fetched using the Coinlore API and displayed in a readable format.

---

## Requirements

- **Python**: Python 3.13 (or any compatible version)
- **Libraries**: No additional libraries are required (uses built-in `urllib` and `json`).

---

## Setup Instructions

1. Ensure you have Python installed. You can download it [here](https://www.python.org/).
2. Copy the script and save it as `crypto_stats.py` using any text editor (e.g., Notepad).
3. Run the script: Open the script in Python 3.13 IDLE and select `Run Module`.


---

## Example Output

```plaintext
--- Global Cryptocurrency Statistics ---
Total Coins: 10300
Active Markets: 30200
Total Market Cap: $1,253,000,000,000.00
Total Volume (24h): $50,000,000,000.00
Bitcoin Dominance: 41.5%
Ethereum Dominance: 17.8%
Market Cap Change (24h): 0.5%
Volume Change (24h): -1.2%
Average Price Change (24h): 0.7%
All-Time High Market Cap: $3,000,000,000,000.00
All-Time High Volume: $250,000,000,000.00
