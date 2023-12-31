# Gemini Telegram Bot

## Introduction
Gemini Telegram Bot is a chatbot powered by the Gemini API, designed to interact with users on the Telegram platform.

## How to Install

### Windows System
1. **Install Dependencies:**
   - Open a Command Prompt or PowerShell window.
   - Navigate to the project directory.
   - Run the following command to install dependencies:
     ```bash
     pip install -r requirements.txt
     ```

2. **Get Telegram Bot API:**
   - Obtain the Telegram Bot API from [BotFather](https://t.me/botfather).

3. **Get Gemini API Keys:**
   - Obtain Gemini API keys from Google AI Studio.

4. **Run the Bot:**
   - In the Command Prompt or PowerShell, run:
     ```bash
     python main.py <Telegram_Bot_API> <Gemini_API_Key>
     ```
     Replace `<Telegram_Bot_API>` and `<Gemini_API_Key>` with your actual API keys.

## How to Use
- Send your questions directly in private messages.
- In group chats, use the `/gemini` command.
- Use the `/clear` command to delete the conversation history.

## References
- [tg_bot_collections](https://github.com/yihong0618/tg_bot_collections)
- [md2tgmd](https://github.com/yym68686/md2tgmd/blob/main/src/md2tgmd.py)
