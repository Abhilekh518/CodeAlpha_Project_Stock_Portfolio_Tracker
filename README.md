# CodeAlpha_Project_Personal-Portfolio-Webs
Create a stock portfolio tracking tool that allows users to add, remove, and track the performance of their stock investments. Utilize financial APIs for real-time stock data.

Step-by-Step Guide to Run Stock Portfolio Tracker

1. Install Python
Make sure you have Python 3.7 or higher installed.
- Download and install Python from: https://www.python.org/downloads/
- Verify installation by running:
  python --version
  or
  python3 --version

2. Get the Project Files
- Clone the GitHub repository if available:
  git clone https://github.com/yourusername/stock-portfolio-tracker.git
  cd stock-portfolio-tracker
- Or download the project files manually and navigate to the folder in your terminal.

3. Create and Activate a Virtual Environment (Optional but recommended)
- On Windows:
  python -m venv venv
  venv\Scripts\activate
- On macOS/Linux:
  python3 -m venv venv
  source venv/bin/activate

4. Install Required Python Packages
Run the following command in your terminal (make sure you're in the project folder or virtual environment):
pip install ttkbootstrap yfinance matplotlib requests

5. Get API Keys
- NewsAPI:
  Sign up at https://newsapi.org/ and get a free API key.
- (ExchangeRate API used in the code is free and doesn't require an API key.)

6. Configure Your API Key
- Open the project file stock_portfolio_tracker.py in a text editor.
- Find the line with:
  NEWSAPI_KEY = "YOUR_NEWSAPI_KEY_HERE"
- Replace "YOUR_NEWSAPI_KEY_HERE" with your actual NewsAPI key as a string.

7. Run the Application
In the terminal (inside the project folder or virtual environment), run:
python stock_portfolio_tracker.py

8. Using the App
- Click Add Stock to enter a stock symbol (e.g., AAPL), number of shares, and buy price.
- Select any stock in the list to view:
  - Its historical price chart (last 6 months).
  - The day’s highest and lowest prices.
  - Latest news headlines related to the stock.
- Use Remove Selected to remove a stock.
- Save your portfolio with Save Portfolio and load it with Load Portfolio.
- Switch between light/dark theme using Toggle Theme.
- The USD to INR exchange rate is displayed at the top.

9. Troubleshooting
- Make sure your internet connection is active.
- Check that the stock symbols you enter are valid.
- If news doesn't load, verify your NewsAPI key and usage limits.
- Errors will show as popups or console output.

If you want me to prepare a ready-to-run .bat or shell script or package the project, just ask!
