### Create and activate venv
```
python3 -m venv save_bot_venv
source save_bot_venv/bin/activate
```

### Create SecretConstants.py with such content
```
BOT_TOKEN = "my_token"
BOT_NAME = "my_bot_name"
BOT_USERNAME = "my_bot_username"
```

### Install [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)

```
python3 -m pip install python-telegram-bot --upgrade   
```

### Run bot
```
python3 main.py
```