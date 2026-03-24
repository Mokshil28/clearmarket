# 📈 ClearMarket 

> **Making stock investing accessible — one plain-English explanation at a time.**

ClearMarket is a full-stack web platform built at **HackDuke 2026** that helps beginners understand the stock market without needing a finance degree. It translates complex financial jargon, analyst opinions, and market news into clear, beginner-friendly language.

## 🔑 Demo Access
**Note:** User registration is currently under maintenance. Please use these credentials to explore the dashboard:
* **User ID:** `test6@example.com`
* **Password:** `password123`

---

## 🧠 The Problem
The barrier to stock investing isn't just money — it's **language**. Financial news is packed with jargon that makes beginners feel shut out. We built ClearMarket to bridge this gap, helping users understand what market information actually means for their portfolio.

## ✨ Key Features
* 🔍 **Jargon Decoder:** Simplifies analyst opinions and financial headlines into beginner-friendly summaries.
* 📊 **Sentiment Analysis:** Highlights market sentiment and the key reasons behind price movements using live feeds.
* 🛡️ **Paper Trading:** A risk-free environment to practice buying and selling stocks to build confidence.
* 🏆 **Leaderboard:** Competitive paper trading to make learning fun and engaging.
* 👤 **Auth & Portfolios:** Personal watchlists and portfolio tracking powered by Supabase.

## 🛠️ Tech Stack
| Layer | Technology |
| :--- | :--- |
| **Frontend** | Next.js 16, React 19, TypeScript, Tailwind CSS v4 |
| **Backend** | Node.js, Express v5 |
| **Database & Auth** | Supabase |
| **AI / LLM** | Groq SDK (High-speed inference) |
| **Market Data** | Finnhub, Yahoo Finance, Alpha Vantage |
| **Social Data** | StockTwits API |

## 🏗️ Project Structure
- `/frontend`: Next.js dashboard, jargon decoder UI, and paper-trading interface.
- `/backend`: Express server handling API logic, Finnhub integration, and news synchronization.
- `main.py`: Python-based data processing and market analysis.
