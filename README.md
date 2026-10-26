MarketPulse-Watchlist

Smart stock monitoring, watchlist intelligence, and portfolio analytics for Indian and US markets.

MarketPulse-Watchlist is a smart market-watch application designed to reduce information overload for investors. Instead of forcing users to continuously monitor every stock, the application highlights meaningful market movements, explains why a stock deserves attention, and provides portfolio-level insights in one place.

🚀 Overview

The application combines:

📊 Portfolio tracking and P&L analysis

👀 Intelligent stock watchlists

📈 Price and market-movement analysis

🔔 Meaningful-movement detection

🎯 Stock attention scores

🌎 Indian and US market support

🧠 Contextual explanations for stock movements

⭐ Personalized stock recommendations

📁 CSV portfolio export

🌓 Light and dark mode

The goal is simple: Which stocks actually need my attention right now, and why?

✨ Key Features

1. Dual Market Support

Switch between Indian Exchange and US Exchange. Examples include RELIANCE.NS, TCS, INFY, AAPL, NVDA, and GOOGL.

2. Smart Watchlist

Add stocks to a personal watchlist and monitor current price, daily movement, trend, attention score, data freshness, and detailed analysis.

3. Meaningful Movement Sensitivity

Choose:

Conservative — focuses on larger movements

Balanced — middle-ground setting

Aggressive — detects smaller movements too

4. Explainable Stock Insights

The stock detail view can show price movement, volume surge, previous close, day range, 52-week range, 50-day average, 200-day average, volume, average volume, score, data source, and update time.

5. Portfolio Analytics

Track invested value, current value, total P&L, P&L percentage, number of holdings, allocation, and profit/loss by holding.

6. Recommendations

A Recommended for You section helps users discover stocks that may be relevant to track.

7. Data Freshness

Stale indicators, cached-data labels, last-update times, and time-since-last-check make data freshness transparent.

8. CSV Export

Export portfolio information for personal analysis and record keeping.

🖥️ Application Pages

Portfolio

Answers: “How is my portfolio performing?” It provides summary statistics, allocation, P&L visualization, and holding-level information.

Watchlist

Answers: “Which stocks should I pay attention to?” It provides tracked stocks, attention scores, meaningful-movement detection, recommendations, and explanations.

Stock Details

Provides price information, trend visualization, score breakdown, historical context, and data freshness information.

🏗️ Project Structure

MarketPulse-Watchlist/
├── backend/
│   ├── app/
│   │   ├── providers/
│   │   │   └── base.py
│   │   ├── ...
│   ├── requirements.txt
│   └── ...
├── frontend/
│   ├── index.html
│   ├── app.js
│   └── ...
├── .gitignore
└── README.md

⚙️ Technology Stack

Frontend: HTML5, CSS3, JavaScript, chart-based visualizations, responsive dashboard UI.

Backend: Python, market-data APIs, data processing/scoring logic, caching and data-freshness handling.

Storage/Data: Market-data APIs, local application database where required, CSV export.

Tools: Visual Studio Code, Python virtual environment, Git, GitHub.

🔄 How It Works

User
  ↓
Select Market (India / US)
  ↓
Add Stocks / View Portfolio
  ↓
Market Data Provider
  ↓
Data Processing
  ├── Price Movement
  ├── Volume Analysis
  ├── Historical Context
  └── Data Freshness
  ↓
Attention Score
  ↓
Watchlist Dashboard
  ↓
Explainable Stock Insights

🧮 Attention Scoring

The watchlist combines signals such as price movement, volume activity, historical context, user-selected sensitivity, and data freshness to determine how much attention a stock may deserve. The score is an attention indicator, not a guaranteed prediction of future returns.

🧠 Future Scope: Machine Learning

At larger scale, machine learning could make the platform more personalized and intelligent:

Personalized recommendations: learn from watchlist behavior, sensitivity, portfolio composition, and preferences.

Anomaly detection: detect unusual price-volume combinations and deviations from historical patterns.

Movement prediction: explore time-series models to estimate the probability of significant movements as an analytical aid.

Intelligent alert timing: learn when users are most likely to want alerts and reduce unnecessary notifications.

Portfolio risk intelligence: identify concentration, sector exposure, similar-stock exposure, and diversification opportunities.

News and sentiment analysis: combine market data with news and public sentiment.

Natural-language explanations: turn multiple signals into simple explanations of why a stock was flagged.

🔐 Security Notes

Do not commit sensitive information to GitHub. Keep API keys, access tokens, passwords, private credentials, and .env files out of the repository. Do not upload backend/.venv/.

🛠️ Installation & Setup

1. Clone the repository

git clone https://github.com/eshitachauhan18/MarketPulse-Watchlist.git
cd MarketPulse-Watchlist

2. Create a virtual environment

cd backend
python -m venv .venv

3. Activate it (Windows)

.venv\Scripts\activate

4. Install dependencies

pip install -r requirements.txt

5. Configure environment variables

If API credentials are required, create a .env file according to the backend configuration. Never commit it.

6. Start the backend

Use the project's Python entry point/configuration. For the current setup this may be:

python main.py

7. Start the frontend

Open frontend/index.html using VS Code Live Server or another local web server. Example:

http://127.0.0.1:5501/index.html

📌 Example Workflow

Open MarketPulse-Watchlist.

Select Indian Exchange or US Exchange.

Open Portfolio to view holdings and P&L.

Go to Watchlist.

Add a stock ticker.

Select a sensitivity level.

Review the attention score.

Open a stock to understand the score.

Explore recommendations.

Export portfolio data when required.

🎯 Problem Statement

Investors face information overload because financial markets generate a large amount of constantly changing data. Simply displaying hundreds of stock prices does not answer the important question: Which change is meaningful enough to investigate?

MarketPulse-Watchlist addresses this by combining market signals, configurable sensitivity, scoring, portfolio analytics, and explainable insights into one interface.

💡 Solution

Raw Market Data → Processed Signals → Attention Score → Explainable Insight

This helps make market monitoring faster, more focused, and easier to understand.

⚠️ Disclaimer

MarketPulse-Watchlist is an educational/project application and is not financial advice. Market data may be delayed, cached, or unavailable depending on the data provider. Attention scores and recommendations should not be treated as guaranteed predictions or investment recommendations. Users should independently verify information before making financial decisions.

📄 Hackathon Submission

Project: MarketPulse-Watchlist
Repository: https://github.com/eshitachauhan18/MarketPulse-Watchlist

👩‍💻 Author

Eshita Chauhan
B.Tech — Computer Science (Artificial Intelligence)

⭐ Project Vision

Don't watch every stock. Watch what matters.

MarketPulse-Watchlist aims to evolve from a market dashboard into an intelligent personal market-monitoring assistant that learns what matters to each investor and presents the most relevant information at the right time.
