# Hungary-fortnite-bot
A fortnite XMPP bot coded in Python with party capabilites.

## How do I get started?

* Install [Python 3.6](https://www.python.org/downloads/release/python-360/ "Python 3.6 Download") (suggested, any 3.x version *should* work, **APART FROM 3.8 DO NOT USE 3.8 OR ELSE YOU'LL GET A LOT OF ERRORS**.)


* Then run ``INSTALL PACKAGES.bat`` if you're on Windows or type these commands into console if you're on macOS / linux:
```
python3 -m pip install -U fortnitepy
python3 -m pip install -U aiohttp
python3 -m pip install -U colorama
python3 -m pip install -U BenBotAsync
```

Then fill out ``config.json`` with your configuration & run the fortnite.py file!

## Commands
For a list of commands, <a href="https://github.com/xMistt/fortnitepy-bot/wiki/Commands">click here.</a>

## Config Documentation
```
"email": "",                                                - The bot accounts email.
"password": "",                                             - The bot accounts password.
"cid": "",                                                  - The skin that the bot wears when it joins.
"bid": "",                                                  - The backpack that the bot wears when it joins.
"eid": "",                                                  - The emote that the bot does when it joins.
"banner": "otherbanner28",                                  - The banner icon the bot uses.
"banner_colour": "defaultcolor15",                          - The colour of the banner icon.
"level": "100",                                             - Sets the clients level.
"bp_tier": 999999999,                                       - Sets the clients battle pass tier.
"status": "Created by xMistt, enjoy! <3",                   - Sets the clients presence.
"platform": "ANDROID",                                      - Sets the clients platform seen in the lobby.
"debug": "False",                                           - If you don't know what this means, ignore it.
"friendaccept": "true"                                      - If the bot will accept every friend request.
```


## How can I contribute?
Fork this repo, add/fix what you want to do and then submit a pull request back.

## Creative Commons License
By downloading this, you agree to the Creative Commons license and that you're not allowed to sell this repository or any code from this repository. For more info see https://commonsclause.com/.
