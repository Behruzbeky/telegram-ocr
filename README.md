# Telegram OCR

Private-chat image transcription only. No answers, translation or explanation.

## Run on a Mac

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Create a local `.env` file containing `TELEGRAM_BOT_TOKEN`, `OPENAI_API_KEY`, and your numeric `ALLOWED_USER_ID`. Never commit it.

```sh
chmod 600 .env
caffeinate -i python bot.py
```

Keep the computer awake and connected. GitHub stores the code; it does not host this bot continuously.
