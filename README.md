<h1 align="center">Google Drive Clone Bot 🔥</h1> 

<hr>

> ## Based on Fclone
## Pre-requisites:-
1. [Install Python 3.7+](https://www.python.org/downloads/)（Latest version 3.8.3 recommended）
2. You'll need service accounts to use this bot.
3. Open **accounts** folder and select any one of the json files and rename it as **1.json**
4. Zip the accounts folder.
5. Create a new bot from Bot Father and get the **Bot token**
6. Get your own Telegram ID.

## Installation:-

```
git clone https://github.com/sawankumar/Google-Drive-Clone-Bot
```

```
pip install -r requirements.txt
```
Open config.ini and fill the appropriate values
```
[General]
path_to_gclone =./fclone

telegram_token = telegram bot token
user_ids = Your Telegram ID (multiple separated by commas, first ID is admin)
group_ids = Your Telegram Group ID (If you are not adding the bot to any group - you can leave it blank)

gclone_para_override = Leave it Blank
```

## Running the Bot
Running in your own System - `python fclone.py`

Running it in Heroku:-

1. Push the Files to Heroku using Heroku CLI
2. Upload the **accounts.zip** to the bot
3. Reply to the message with `/sa`
4. Type /`folders` and set your favourite Folders
5. Send or forward a message with a Google Drive link to the bot to start copying...

## Deploy on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/sawankumar/Google-Drive-Clone-Bot/tree/master)
