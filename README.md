# Group Music Bot

### HEROKU VARAS

API_ID _༆IT CAN BE FOUND ON_➪[OFFICIAL WEB ](http://my.telegram.org )

API_HASH _༆SAME AS API ID_➪[OFFICIAL WEB ](http://my.telegram.org )

BOT_TOKEN_༆IT CAN BE FOUND ON TELEGRAM_➪[BOT FATHER](http://t.me/BotFather)

DURATION_LIMIT _༆IT IS AN INTEGER FOR DURATION LIMIT OF SONGS THE TM DEFAULT VALUE IS 10 M SO YOU CAN SET UPTO 60 MINUTES_ (In minutes ).

SESSION_NAME _༆THAT PYROGRAM STRING SESSION CAN BE FOUND BELOW_

SUDO_USERS _༆LIST OF TG USER ID's IS COUNTED AS AS ADMIN EVERYWHERE.(separated by space)_

**PYROGRAM STRRING⤵️

<a href="https://t.me/ScrapperRoBot" target="_blank"><img src="https://img.shields.io/badge/run-string__session.py-green?style=for-the-badge&logo=repl.it" alt="generate_string" /></a>   

## Click Here

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://github.com/v-v-r-official/GroupMusicBot/blob/main/README.md#heroku)


## Note

Neither this, or PyTgCalls are fully stable.

## Requirements

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.7+
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)

## Deployment

### Config

Copy `example.env` to `.env` and fill it with your credentials.

### Without Docker

1. Install Python requirements:
   ```bash
   pip install -r requirements.txt
   ```
2. Run:
   ```bash
   python main.py
   ```

### Using Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```

### Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/v-v-r-official/24-7Music)


## Credits

- [Roj](https://github.com/rojserbest): main developer
- [Marvin](https://github.com/BlackStoneReborn): bug reporter
- [Laky](https://github.com/Laky-64) & [Andrew](https://github.com/AndrewLaneX): PyTgCalls
