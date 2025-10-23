📊 AI Stock Research Agent (CrewAI)

An intelligent multi-agent system built with CrewAI that autonomously analyzes public companies using real-time Yahoo Finance data and SEC filings.
The agents collaborate to collect, interpret, and summarize key financial information such as earnings, valuation ratios, and business segments — producing concise, human-readable investment insights.

🚀 Features

🤖 Multi-Agent Workflow – Modular CrewAI agents specialized in stock fundamentals, financial metrics, and price analysis.

🧾 SEC Filing Integration – Fetches official 10-K and 10-Q reports via the SEC API
 for transparent fundamental data.

💹 Yahoo Finance Tool – Retrieves live market data: current price, market cap, P/E ratio, dividend yield, and company summary.

📈 Autonomous Reasoning – Agents use structured thought/action loops to decide which data to query and when.

🧠 Configurable Tasks – YAML-based task and agent definitions make it easy to extend or customize analysis workflows.

🛠️ Tech Stack

CrewAI – Agent-oriented orchestration framework

Python 3.10+

Yahoo Finance (yfinance) – Market data API

SEC-API – SEC filings search API

Pydantic + Requests – Validation and HTTP requests
