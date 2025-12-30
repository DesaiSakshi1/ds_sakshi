# ds_sakshi
Data Science Assignment – Web3 Trading Team
Candidate: Sakshi
Date: 31 December 2025
Position: Data Science Internship
________________________________________
 Project Structure
ds_sakshi/
├── notebook_1.ipynb          # Main analysis notebook
├── notebook_2.ipynb          # Advanced analysis (optional)
├── csv_files/                # All CSV outputs
│   ├── merged_trading_sentiment.csv
│   ├── summary_statistics.csv
│   └── trader_profiles.csv
├── outputs/                  # All visualizations
│   ├── 1_trading_volume_by_sentiment.png
│   ├── 2_buy_sell_distribution.png
│   ├── 3_avg_trade_size.png
│   ├── 4_pnl_by_sentiment.png
│   ├── 5_trading_activity_timeline.png
│   ├── 6_sentiment_distribution.png
│   ├── 7_trade_size_boxplot.png
│   ├── 8_correlation_heatmap.png
│   ├── 9_hourly_trading_patterns.png
│   ├── 10_trader_profiling.png
│   ├── 11_risk_analysis.png
│   └── 12_feature_importance.png
├── ds_report.pdf             # Final summarized insights and explanations
└── README.md                 # Project documentation
________________________________________
🎯 Assignment Overview
This project analyzes the relationship between trader behavior on the Hyperliquid trading platform and Bitcoin market sentiment using the Fear & Greed Index. The goal is to identify how market psychology influences trading volume, profitability, risk behavior, and trade direction, and to extract insights that could support smarter trading strategies.
________________________________________
 Datasets Used
1️ Historical Trader Data (Hyperliquid)
Includes trade-level details such as:
•	Account
•	Coin
•	Execution Price
•	Size (Tokens & USD)
•	Side (BUY / SELL)
•	Timestamp (IST)
•	Closed PnL
•	Fee
2️ Fear & Greed Index
Includes daily market sentiment information:
•	Date
•	Classification (Extreme Fear, Fear, Neutral, Greed)
•	Sentiment Value
________________________________________
 How to Run the Project
Prerequisites
•	Google Colab account (recommended)
•	Python 3.7 or above
•	Required libraries:
o	pandas
o	numpy
o	matplotlib
o	seaborn
o	scipy
o	scikit-learn
o	plotly
________________________________________
Step 1: Run Notebook 1 (Main Analysis)
1.	Open Google Colab: https://colab.research.google.com
2.	Upload notebook_1.ipynb
3.	Run all cells sequentially
4.	Upload the required CSV datasets when prompted
This notebook performs:
•	Data loading and cleaning
•	Data merging with sentiment data
•	Exploratory Data Analysis (EDA)
•	Statistical testing
•	Visualization generation
________________________________________
Step 2: Review Outputs
After running Notebook 1:
•	Cleaned and merged datasets are saved in csv_files/
•	All charts are saved in outputs/
•	Console output provides statistical summaries and insights
________________________________________
Step 3: Run Notebook 2 (Optional – Advanced Analysis)
Upload and run notebook_2.ipynb to perform:
•	Time-based trading pattern analysis
•	Trader profiling and segmentation
•	Sentiment transition analysis
•	Risk and volatility analysis
•	Feature importance using predictive modeling
________________________________________
Key Analyses Performed
Exploratory Analysis
•	Trading volume by sentiment
•	Buy vs Sell behavior
•	Trade size distribution
•	Temporal trading patterns
Profitability & Risk Analysis
•	Closed PnL comparison by sentiment
•	Volatility and risk metrics
•	Statistical hypothesis testing
Advanced Analytics
•	Trader segmentation
•	Sentiment transition behavior
•	Feature importance analysis
________________________________________
 Final Report
The file ds_report.pdf contains:
•	Executive summary
•	Detailed analysis and interpretations
•	Visual evidence and statistical findings
•	Trading strategy implications
•	Limitations and future work
________________________________________
 Links
Google Colab Notebooks
•	Notebook 1 (Main Analysis): https://colab.research.google.com/drive/1uUQdtawREJ26QJEeXppyxH65eiEzWXkj?usp=sharing
•	Notebook 2 (Advanced Analysis): https://colab.research.google.com/drive/1ikwt44u4JftBqFdBPI_lD68p1ArDOzWS?usp=sharing
GitHub Repository
•	Repository Link: https://github.com/DesaiSakshi1/ds_sakshi
Note: All Google Colab links are set to “Anyone with the link can view”.
________________________________________
 Technologies Used
•	Python
•	Pandas & NumPy
•	Matplotlib & Seaborn
•	Plotly
•	SciPy
•	Scikit-learn

