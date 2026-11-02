\# 🚀 n8n Crypto Market Report \& AI Analyst Bot



An automated and intelligent system built with \*\*n8n\*\* that automatically fetches live prices for top 10 cryptocurrencies, generates AI-powered market analysis and daily predictions using \*\*OpenAI\*\*, and publishes formatted reports directly to a \*\*Telegram channel\*\* on a scheduled basis.



\---



\## ✨ Features

\- \*\*Automated Price Fetching:\*\* Integrates with reliable APIs (CoinGecko) to retrieve real-time prices and 24h changes for top cryptocurrencies (BTC, ETH, USDT, BNB, SOL, XRP, ADA, DOGE, AVAX, TRX).

\- \*\*AI Analyst Agent:\*\* Uses OpenAI language models to write concise market summaries and daily bullish/bearish predictions in fluent Persian.

\- \*\*Advanced Formatting:\*\* Clean Telegram HTML formatting (`<b>`, `<i>`) combined with dynamic status icons (🟢▲ / 🔴▼).

\- \*\*Flexible Scheduling:\*\* Cron-based scheduling to run automated updates at customized intervals (e.g., hourly from 9 AM to 11 PM Tehran time).



\---



\## 🛠️ Tech Stack

\- \[n8n](https://n8n.io/) (Self-hosted via Docker)

\- OpenAI API (GPT-4o-mini)

\- Telegram Bot API

\- JavaScript (Data merging and formatting)



\---



\## 🏗️ Workflow Structure

1\. \*\*Schedule Trigger:\*\* Triggers the workflow based on configured Cron expressions.

2\. \*\*HTTP Request:\*\* Fetches raw cryptocurrency market data.

3\. \*\*AI Agent:\*\* Processes the data and generates professional market insights.

4\. \*\*Code Node (JavaScript):\*\* Merges pricing data with AI analysis into a single structured message.

5\. \*\*Telegram Node:\*\* Delivers the final formatted report to the Telegram channel.



\---



\## ⚙️ Installation \& Setup



1\. Deploy your self-hosted n8n instance using Docker/Docker Compose.

2\. Import the provided workflow JSON file into your n8n dashboard.

3\. Configure your credentials and parameters:

&#x20;  - \*\*Telegram Bot Token \& Chat ID\*\* (Ensure the bot is an administrator in your channel).

&#x20;  - \*\*OpenAI API Key\*\* (For the AI Agent node).

4\. Set the workflow Timezone to `Asia/Tehran` in workflow settings.

5\. Toggle the \*\*Active\*\* switch to turn on automation.





