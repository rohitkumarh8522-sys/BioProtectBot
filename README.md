# Telegram Bio Link Protection & Auto Delete Bot

## Overview
A Pyrogram-based Telegram Bot that detects links or channel handles (@) in user bios and automatically bans them upon sending a message. Features auto-message deletion and private owner controls (`/stats` and `/broadcast`).

## Setup Instructions

1. **Install Requirements:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Configure Credentials in `main.py`:**
   - `API_ID`: Get from https://my.telegram.org
   - `API_HASH`: Get from https://my.telegram.org
   - `BOT_TOKEN`: Get from @BotFather
   - `OWNER_ID`: Your numeric Telegram ID (get from @userinfobot)

3. **Run the Bot:**
   ```bash
   python main.py
   ```
