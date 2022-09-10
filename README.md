# qobuz-dl-telegram-bot

## Commands for bot(set through @BotFather)

```
start - start bot
download - dl one link and multi link
status - bot status
log - log

```
1. **Installing requirements**

 - Clone repo:

        git clone https://github.com/rinrinx/qobuz-dl-telegram-bot

2. **Set up config file**

- config.env 

- Fill up variables:

   - Mandatory variables:
   
        - `API_ID`: get this from https://my.telegram.org. Don't put this in quotes
        - `API_HASH`: get this from https://my.telegram.org
        - `BOT_TOKEN`: The Telegram Bot Token (get from @BotFather)
        - `OWNER_ID`: your Telegram User ID (not username) of the owner of the bot
        - `AUTH_IDS`: Group Id -100xxxx
        - `QOBUZ_MAIL`: qobuz email
        - `QOBUZ_PASS`: qobuz pass
        - `QOBUZ_QUAL`: Quality
        - `LOG_CHANNEL`: Channel Id -100xxxx


🌿 Quality
```
  5:  MP3-320 Kbps
  6:  CD-16-bit/44,1 kHz
  7:  24-Bit Hi-Res/Upto 96 kHz
  27: 24-Bit Hi-Res/Upto 192 kHz
```
