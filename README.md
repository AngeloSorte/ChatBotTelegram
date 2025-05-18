# Basic AI Chatbot for Telegram

This is a simple Telegram chatbot built with Python and the `python-telegram-bot` library.  
The chatbot has a pre-set conversation flow with fixed responses and can be used as a basic chatbot service for websites or Telegram.

## Features

- Telegram bot integration  
- Pre-set conversation flow with basic commands  
- Easy to customize and extend  
- Simple to deploy and test

## Requirements

- Python 3.7 or higher  
- Telegram Bot Token (from BotFather)  
- Libraries listed in `requirements.txt`

## Installation

1. Clone this repository:  
   
   git clone https://github.com/yourusername/basic-ai-chatbot.git
   cd basic-ai-chatbot
Install dependencies:

pip install -r requirements.txt
Set your Telegram bot token in the script (bot.py):

TOKEN = "YOUR_TELEGRAM_BOT_TOKEN"

Run the bot script:

python bot.py

Your bot will start and listen for messages on Telegram.
Test your bot by sending messages or commands.

How it works

The bot uses python-telegram-bot to handle messages.
It replies based on a pre-defined conversation flow coded in the handlers.

You can add more commands and message handlers in bot.py to extend the bot's functionality.

Author
Angelo Sorte - truthseekers1983@gmail.com

License
This project is licensed under the MIT License.
