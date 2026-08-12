# 📈 NSE Stock Research & Analysis System

A sophisticated multi-agent AI system for analyzing Indian NSE-listed stocks using real-time data, technical indicators, news sentiment, and advanced AI reasoning.

## 🌟 Features

### 🤖 Multi-Agent Architecture
- **Stock Finder Agent**: Identifies promising NSE stocks based on liquidity, market cap, and momentum
- **Market Data Agent**: Gathers real-time pricing, volume, and technical indicators  
- **News Analyst Agent**: Analyzes recent news sentiment and market impact
- **Recommendation Agent**: Provides actionable BUY/SELL/HOLD recommendations with target prices

### 📊 Advanced Analytics
- Real-time NSE stock data integration
- Technical indicators (RSI, Moving Averages, MACD)
- Volume and volatility analysis
- News sentiment classification
- Risk-reward assessment

### 🎯 Smart Recommendations
- Specific entry/exit price points
- Stop-loss levels and risk management
- Confidence scoring for each recommendation
- Time horizon-based analysis (short-term to medium-term)

### 🎨 Modern UI
- Clean, responsive Streamlit interface
- Interactive charts and visualizations
- Real-time status updates
- CSV export functionality
- Mobile-friendly design

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Bright Data API account ([Sign up here](https://brightdata.com))
- OpenAI API key ([Get one here](https://platform.openai.com))


## 📈  Output

```
🎯 TRADING RECOMMENDATIONS
═══════════════════════════════════

RELIANCE - Reliance Industries Limited
─────────────────────────────────
📋 RECOMMENDATION: BUY
🎯 TARGET PRICE: ₹2,650
⏰ TIME HORIZON: 1-3 days
📊 CONFIDENCE: HIGH

📈 ENTRY STRATEGY:
Current Price: ₹2,450
Suggested Entry: ₹2,430 - ₹2,460
Stop Loss: ₹2,380 (3.2% below entry)
Target: ₹2,650 (8.2% upside potential)

💡 RATIONALE:
Technical: Breakout above 50-day MA with strong volume
Fundamental: Positive earnings guidance + new project announcements
Risk-Reward: 1:2.6 ratio
```

## 🏗️ System Architecture

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Streamlit UI  │────│   Supervisor     │────│  Bright Data    │
│                 │    │     Agent        │    │   MCP Server    │
└─────────────────┘    └──────────────────┘    └─────────────────┘
                              │
                    ┌─────────┼─────────┐
                    │         │         │
            ┌───────▼───┐ ┌───▼───┐ ┌───▼────┐
            │Stock Finder│ │Market │ │News    │
            │   Agent    │ │Data   │ │Analyst │
            └────────────┘ │Agent  │ │Agent   │
                          └───────┘ └────────┘
                                │
                        ┌───────▼────────┐
                        │ Recommendation │
                        │     Agent      │
                        └────────────────┘
```

## 🔍 Agent Details

### Stock Finder Agent
- Scans NSE universe for liquid, high-potential stocks
- Filters by market cap, volume, and momentum criteria
- Avoids penny stocks and illiquid securities
- Focuses on large-cap and mid-cap opportunities

### Market Data Agent  
- Real-time price, volume, and market data
- Technical indicators (RSI, MACD, Moving Averages)
- Support/resistance level identification
- Trend analysis and momentum assessment

### News Analyst Agent
- Scrapes recent financial news and announcements
- Sentiment classification (Positive/Negative/Neutral)
- Impact assessment on stock prices
- Catalyst identification for price movements

### Recommendation Agent
- Synthesizes all data into actionable recommendations
- Provides specific entry/exit strategies
- Risk management and position sizing guidance
- Confidence scoring and time horizon analysis

## 🛡️ Risk Management Features

- **Stop-loss recommendations** for every trade suggestion
- **Position sizing guidance** based on volatility
- **Risk-reward ratio analysis** (minimum 1:2 ratio)
- **Confidence scoring** to help with decision making
- **Time horizon specification** for each recommendation

## 📊 Export & Reporting

- **CSV Export**: Download analysis results for further analysis
- **Interactive Charts**: Visualize current vs target prices
- **Performance Tracking**: Monitor recommendation accuracy
- **Historical Analysis**: Compare predictions with actual outcomes

## ⚠️ Important Disclaimers

- This tool is for **educational and research purposes only**
- Always consult with a qualified financial advisor before investing
- Past performance does not guarantee future results
- The Indian stock market involves substantial risk of loss
- Do your own due diligence before making any investment decisions


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
---
### 👩‍💻 Author
**Ishpreet Singh**

M.Tech
Indian Institute of Technology Bombay
Mail ID:
25m0326@iitb.ac.in
---




   ```


