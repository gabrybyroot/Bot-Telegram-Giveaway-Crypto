# Giveaway Bot🤖

**Disclaimer:**
I do not assume any responsibility for the use of these files by any user. I recommend using them solely for educational, professional, or testing purposes. Feel free to implement the code and make any necessary modifications with comments.

## Description:
Giveaway Bot🤖 is a Telegram bot designed for user registration and giveaways on the Bep-20 crypto wallet. The bot facilitates the giveaway process on Telegram, allowing users to register and participate in the giveaway.

## Dependencies:
- [python-telegram-bot](https://pypi.org/project/python-telegram-bot/)
- [openpyxl](https://pypi.org/project/openpyxl/)

## Install Dependencies
Make sure you have Python installed. You can install the required dependencies using pip:
pip install -r requirements.txt

## Add your token (Line 154)
Make sure to replace "YOUR_BOT_TOKEN" with the actual token provided by BotFather.

## Running Bot:
python main.py

## Command Bot Telegram:
- `/wallet <Bep-20 Address>`: Set or update your Bep-20 wallet address.
  Example: `/wallet 0xAbCdEfGh1234567890`
  
- `/data`: Check your registration information.
  Example: `/data`

- `/accept`: Accept terms and conditions to participate.
  Example: `/accept`

- `/leaderboard`: View the top 10 users.
  Example: `/leaderboard`

- `/help`: Contact support.
  Example: `/help`

- `/regard`: Get information about the giveaway and prize.
  Example: `/regard`

**Note:** Additional information about commands and usage may be available within the bot.
