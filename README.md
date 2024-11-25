# IBKR Trading Automation Project

This project uses the Interactive Brokers (IBKR) API to perform various trading-related functions. The functions include retrieving instrument details, positions, holdings, OHLC data, margins, placing orders, and getting market quotes.

## Prerequisites

- Python 3.8 or later
- An IBKR account with API access
- Necessary market data subscriptions

## Setup Instructions

### Step 1: Clone the Repository

Clone the repository to your local machine:


git clone https://github.com/yourusername/ibkr-trading-automation.git
cd ibkr-trading-automation


Step 2: Create and Activate a Virtual Environment
Create a virtual environment to manage dependencies:

Windows:
  python -m venv venv
.\venv\Scripts\activate

macOS/Linux:

  python3 -m venv venv
  source venv/bin/activate

  Step 3: Install Dependencies
Install the required libraries using the provided requirements.txt file:
             pip install -r requirements.txt

requirements.txt Content
       ib_insync==0.9.70
       pandas==1.5.3
       tabulate==0.9.0
       nest_asyncio==1.5.6



Usage
Running the Main Script
To start the interactive menu, run:
        python main.py


Interactive Menu Options

View Holdings
View Positions
Get Candlestick Data
View Margin
Place a Trade
Get Quote Data
Exit

Example Workflow
Start the Interactive Menu: Run python main.py.
Choose an Option: Enter the number corresponding to the desired action (e.g., "1" to view holdings).
Follow Prompts: For options that require additional input (e.g., stock symbol, dates), follow the on-screen prompts.
Notes
Ensure IBKR Trader Workstation (TWS) or IB Gateway is running before executing the scripts.
Update the connection port in the script for live trading if necessary (default is set for paper trading).
The script uses the auth token for API access; ensure it is correctly configured.




This README includes all the setup instructions, usage information, and the required dependencies, all in one file for easy reference.
