# 📰 Telegram News Bot 🤖

A Python-powered Telegram bot that fetches and delivers **real-time news updates** directly into your Telegram chat. Stay informed with the latest headlines across various categories—on demand!


<img width="596" alt="Screenshot 2025-05-01 223600" src="https://github.com/user-attachments/assets/f09e3156-0c62-44a2-a7da-a20cf7b85aee" />
<img width="446" alt="Screenshot 2025-05-01 223650" src="https://github.com/user-attachments/assets/40503c21-810d-406b-89f7-2589d18556d4" />

---

## 🚀 Features

- 🔄 Real-time news updates from trusted sources (e.g., CBS Sports, CNBC)
- 💬 Simple command interface (`/start`, `/news`, `/subscribe`, `/help`)
- 🧠 Personalized news categories (sports, politics, tech, etc.)
- 🖼️ Rich media: Headlines with images, summaries, and source links
- 🧾 Instant previews using Telegram's native features


---

## 🛠️ Built With

- **Language**: Python 3.9+
- **News Fetching**: `requests`, `BeautifulSoup` *(for scraping)* or third-party news APIs like [NewsAPI](https://newsapi.org/)
- **Deployment**: [Replit](https://replit.com/) and Local Python
- **Data Parsing**: JSON, HTML parsing
- **Optional**: `APScheduler` for scheduled updates

---

## 📦 Installation

### ✅ Option 1: Run on Replit

1. **Fork the Replit project** or upload your code.
2. **Add secrets**:
   - Go to the padlock icon 🔒 in Replit
   - Add these environment variables:
     ```
     TELEGRAM_BOT_TOKEN = your_telegram_bot_token
     NEWS_API_KEY = your_newsapi_key
     ```
3. **Click Run ▶️** to start the bot.

✅ Replit stays online if you use **uptimer services** (e.g., UptimeRobot) to keep it active.
