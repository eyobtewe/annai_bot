# TelegramGPT
TelegramGPT is a Telegram bot that uses OpenAI's GPT-3 language model to generate responses to user messages. The bot is designed to be concise and polite in its answers, and can respond to both text and voice messages.

## Installation
To run TelegramGPT, you will need to set up a few things first:

Clone this repository to your local machine.
Create a virtual environment and activate it.
Install the required Python packages by running 
```
pip install python-telegram-bot==13.0
pip install openai
pip install moviepy
pip install python-dotenv

```
Create a .env file in the project directory and add your OpenAI API key and Telegram bot token. The file should look like this:

```
OPENAI_API_KEY=<your api key>
TELEGRAM_BOT_TOKEN=<your bot token>
```
## Usage
To start the bot, run the main.py file:


```
python main.py
```
The bot will start running and will listen for incoming messages. To talk to the bot, simply send a message to it on Telegram.

TelegramGPT can respond to both text and voice messages. When you send a voice message, the bot will transcribe the message and generate a response based on the transcription.

## Limitations
TelegramGPT is powered by OpenAI's GPT-3 language model, which has some limitations:

- The model may generate responses that are biased or inappropriate. Please use the bot responsibly.
- The model is not perfect and may make mistakes or generate responses that do not make sense.

