# JARVIS

<p align="center">
<img src="jarvis.jpg" alt="JARVIS USERBOT">


[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)



Best User Bot To Manage Your Telegram Account 
## Most PowerFul And Better And Secure

## By Team #J.A.R.V.I.S™

### Inspired By Friday
### Credits : FridayUserBot
###               CatUserbot
###               WolfUserBot          
###               Munnipopz
 
### This Bot is Made With care No Adult Contents and Abusive Memes. If Any Tell in Issue Column With Command Name.
### For any query or want to know how it works join Group And Channel 

<a href="https://t.me/jarvissupportofficial"><img src="https://img.shields.io/badge/Join-Telegram%20Channel-red.svg?logo=Telegram"></a>
<a href="https://t.me/joinchat/R5-ZBEdh9Uzix53RWtmHiA"><img src="https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=telegram"></a>

## Installing Heroku 

### The Easy Way
[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2Fjarvis210904%2FJ.A.R.V.I.S-Userbot&template=https%3A%2F%2Fgithub.com%2Fjarvis210904%2FJ.A.R.V.I.S-Userbot)

## GET STRING SESSION FROM REPL RUN 

[![Run on Repl.it](https://repl.it/badge/github/jarvis210904/Jarvis)](https://jarvis.jarvis210904.repl.run)


### The Normal Way

Simply clone the repository and run the main file:
```sh
git clone https://github.com/jarvis210904/JARVISuserbot/
cd Userbot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m userbot
```

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```


### UniBorg Configuration


The UniBorg Config is situated in `userbot/uniborgConfig.py`.

**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**
Fortunately there are no Mandatory vars for the UniBorg Support Config.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars.

