# 📰 DDAB Bot – Daily Data Aggregator Bot

**DDAB Bot** is an AI-powered daily briefing tool that pulls essential information from multiple sources and presents it in a single, concise report. Think of it as your "day at a glance" companion — customizable, modular, and lightning-fast.

---

## 🚀 Features

- **Weather Updates** – Current conditions, highs/lows, severe alerts.
- **Current Events** – Local & global headlines.
- **Entertainment News** – TV, movies, celebrity trends.
- **Sports Scores & Fixtures** – Latest results & upcoming matches.
- **Tech & Science** – Innovations, discoveries, and cybersecurity alerts.
- **Finance Data** – Market indexes, currency rates, crypto prices.
- **Productivity Tools** – Google Calendar/Outlook integration, to-do lists.
- **Fun Extras** – Quote of the day, historical facts, custom feeds.

---

## 📦 Modules

DDAB Bot is **modular**, meaning you can turn features on or off:

| Module               | Status | Description |
|----------------------|--------|-------------|
| Weather              | ✅     | Pulls local/tomorrow forecast and alerts. |
| News                 | ✅     | Aggregates top headlines from multiple APIs. |
| Entertainment        | ✅     | Tracks TV, movie, music, celebrity news. |
| Sports               | ✅     | Scores, fixtures, and live updates. |
| Finance              | ✅     | Market, currency, and crypto stats. |
| Productivity         | 🔄     | Sync tasks and events from popular tools. |
| Fun Extras           | ✅     | Quotes, trivia, and “on this day” facts. |

---

## 🛠 Tech Stack

- **Backend**: Python / FastAPI (modular architecture)
- **Data Sources**: Public APIs (NewsAPI, OpenWeather, TMDB, etc.)
- **AI Layer**: Optional summarization via OpenAI or LLaMA
- **Deployment**: Docker-ready for cloud or local hosting

---

## 📥 Installation

```bash
# Clone the repo
git clone https://github.com/prav-raghu/daily-data-aggregator-bot.git
cd daily-data-aggregator-bot

# Install dependencies
pip install -r requirements.txt

# Run the bot
python main.py
