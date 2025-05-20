# 📈 Multi-Agent Stock Market Analysis System

This project is an intelligent **multi-agent system** designed to analyze a company's stock and evaluate its investment potential using OpenAI's LLMs and the `autogen` framework. The system simulates a collaborative team of agents, each playing a specialized role in the analysis pipeline—from market research to financial assessment to risk advisory.

---

## 🧠 System Overview

The system includes four key agents working in sequence:

1. **User Proxy Agent** (`Stock_Analyst`)  
   Acts as the human initiator, triggering the analysis workflow with a company name or stock ticker.

2. **Market Researcher Agent** (`market_researcher`)  
   Gathers up-to-date stock data, analyst recommendations, relevant news, and industry trends.

3. **Financial Analyst Agent** (`financial_analyst`)  
   Evaluates key financial metrics such as P/E ratio, Market Cap, and EPS, and compares them with industry benchmarks.

4. **Risk Advisor Agent** (`risk_advisor`)  
   Assesses risks including market volatility, regulatory concerns, and macroeconomic conditions, providing investment caution.

---

## 🧩 Key Features

- ✅ **Multi-Agent Collaboration:** Each agent has a distinct role and communicates in a structured sequence.
- ✅ **LLM-Driven Chain-of-Thought:** Thoughtful, step-by-step analysis across agents.
- ✅ **Stock & Market Intelligence:** Integrates latest stock prices, news, and trends.
- ✅ **Financial Health Check:** Benchmarks company metrics against the industry.
- ✅ **Risk Disclosure:** Identifies critical investment risks and uncertainties.
- ✅ **Autogen Framework:** Uses the `pyautogen` and `autogen` libraries for multi-agent orchestration.

---
