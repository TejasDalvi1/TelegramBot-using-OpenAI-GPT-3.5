===============================================================================
# TelegramBot-using-OpenAI-GPT-3.5
===============================================================================

## Tech stack:
        (1)Python
        (2)aiogram
        (3)OpenAI GPT-3.5-turbo        
-------------------------------------------------------------------------------

## Steps to run:

### (1) Create Environment
```bash
conda create -n llmenv python=3.10 -y
```
```bash
conda activate llmenv
```

### (2) Install "requirements.txt"
```bash
pip install -r requirements.txt
```

### (3) Create a `.env` file in the root directory and add your credentials:
```ini
OPENAI_API_KEY = "Put_Your_Key"
```
```ini
TELEGRAM_BOT_TOKEN = "Put_Your_token"
```
### (4) Run the following
```bash
python telegram_bot.py
```

### (5) Open Telegram app and chat with created bot.
-------------------------------------------------------------------------------