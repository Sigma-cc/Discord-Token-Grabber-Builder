<p align="center">A Discord token grabber written in Python 3.</p>
*<p align="center"> Python 3.6+</p>

*This version of the grabber only supports **Windows**.*
***
# Features
* No local caching

* Grabber supports multiple directories
    - [x] Discord, Discord Canarry, Discord PTB
    - [x] Google Chrome, Opera, Brave, Yandex
    - [ ] Firefox

* Allows you to send tokens in discord / telegram
***
# Preview
### Discord:
*`WEBHOOK_STYLE : True(Slower)`*
![](https://media.discordapp.net/attachments/769178644697972767/798917458840518696/unknown.png?width=341&height=567)
***
*`WEBHOOK_STYLE : False`*
![](https://media.discordapp.net/attachments/769178644697972767/798918343061929994/unknown.png)
***
### Telegram:
*`TELEGRAM_STYLE : True(Slower)`*
![](https://media.discordapp.net/attachments/769178644697972767/798919478548103168/unknown.png)
***
*`TELEGRAM_STYLE : False`*
![](https://media.discordapp.net/attachments/769178644697972767/798921203824984093/unknown.png)
***

# How to use:
#### Installing Telegram:
```console
$ python -m pip install telegram
```
#### Discord
1. Create a webhook on your Discord server.
2. Change the `WEBHOOK_URL` variable value to your Discord webhook URL in [token-grabber.py](token-grabber.py)
3. Change as desired `WEBHOOK_STYLE` to `True`(Slower) or `False`

#### Telegram
1. Receive a bot token through [Bot Father](https://t.me/botfather)
2. Send to the newly created bot `/start`
3. Get your telegram id with [Get my id bot](https://t.me/getmyid_bot)
4. Paste token to `TELEGRAM_BOT_TOKEN` and your telegram id to `TELEGRAM_USER_ID` in [token-grabber.py](token-grabber.py)
5. Change as desired `TELEGRAM_STYLE` to `True`(Slower) or `False`

##### Done, now you can compile `token-grabber.py` to `.exe` with [pyinstaller](https://pypi.org/project/pyinstaller/)
***
## Author
- **wodx**
    - [Github](https://github.com/wodxgod)
    - [PayPal.me](https://www.paypal.com/paypalme2/wodx)

## Donate
You can donate to author PayPal at https://www.paypal.com/paypalme2/wodx <3
***
# Legality
Everything you can see here has been made for educational purposes and proof of concepts. I do not promote the usage of my tools, I do not take responsability on the bad usage of this tool.
