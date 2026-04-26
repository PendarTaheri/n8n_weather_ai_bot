# AI Smart Weather Bot (n8n + Mistral AI)

A powerful automation workflow built with **n8n** that fetches weather data and provides intelligent daily summaries via **Telegram**.

## Features
- **Smart Summaries:** Uses **Mistral AI** to analyze weather conditions and provide personalized clothing or activity advice.
- **Scheduled Reports:** Automatically triggers at specific intervals (e.g., every hour or daily) using the **Schedule Trigger**.
- **Telegram Integration:** Sends real-time notifications directly to your Telegram bot.
- **Local/Cloud Ready:** Can be hosted on a local machine or deployed to a VPS/Cloud environment.

## Tech Stack
- **n8n:** Workflow automation platform.
- **Mistral AI:** High-performance LLM for weather analysis.
- **Telegram Bot API:** For message delivery.
- **OpenWeatherMap API:** (Optional/Included) for fetching raw weather data.

## How to Use
1. **Import the Workflow:** Download the `weather-bot.json` file and import it into your n8n instance.
2. **Setup Credentials:**
   - Add your **Mistral AI API Key**.
   - Add your **Telegram Bot Token** and **Chat ID**.
3. **Configure Schedule:** Adjust the `Schedule Trigger` node to your preferred time.
4. **Publish:** Hit the 'Publish' button to start receiving your smart weather updates!

## License
This project is open-source and available under the MIT License.
