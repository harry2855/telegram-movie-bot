<p align="center"><a href="https://akkupy.me"><img src="https://github.com/akkupy/Sara-Bot/blob/main/Assets/Sara_Bot.jpg" width="5000"></a></p> 
<h1 align="center"><b>SARA-BOT </b></h1>
<h4 align="center">A Powerful, Smart And Simple Telegram Bot By Akku</h4>

> **Warning** <br>
> It Just Forwards the Movie or the file that is saved via /save command.Use it at your own risk .I'm not responsible for sharing copyrighted content with this program.

# KeyFeatures

- Movie Information Searching.
- Trailer Support.
- IMDB Links.
- Information On TV Series.

# Prerequisite

- [Python 3.11+](https://www.python.org/downloads/)
- [Telegram Bot API](https://telegram.me/BotFather)
- [OMDB API](https://www.omdbapi.com/)
- [TMDB API](https://developer.themoviedb.org/reference/intro/getting-started)
- [MySQL Server](https://www.mysql.com/)

# Environment Variables

```
[+] If You Running Sara On A Deploy Services With Config Env Support Like Heroku, Zeet.co, Please Set "ENV" To True , Else For Self Host Services Like Digital Ocean Just Make A Credentials File And Put Vars Given Below.
    [-] BOT_API:   Telegram Bot Token
    [-] OMDB_API :   OMDB Api Token
    [-] BOT_USERNAME : Telegram Bot Username
    [-] TMDB_API : TMDB Api Token
    [-] MYSQL_HOST = MySQL Server Host
    [-] MYSQL_USER = MySQL User
    [-] MYSQL_PASSWORD = MySQL Password
    [-] MYSQL_DATABASE = MySQL Database Name
    [-] CREATE_TABLE = True/False (Set to True if tables doesn't exist.)

[+] The Sara will not work without setting the environment variables.
```

## An Example Of ".env" File

```

BOT_API = "sd78g6add897s8d7f875adad768d"
BOT_USERNAME = "akkubot"
OMDB_API = "d3w35frsd34scv"
TMDB_API = "dwa3r43rfsd344r4"
MYSQL_HOST = '10.1.1.50'
MYSQL_USER = 'root'
MYSQL_PASSWORD = 'root'
MYSQL_DATABASE = 'telegram'
CREATE_TABLE = False
```
