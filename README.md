If you would like the bot to work, you will need to
replace the "token" and "sqlpass" field in "config.json"
with your bot's token and MySQL database password. I have 
omitted the "config.json" file for security reasons. The
"config.json" is described by the following: <br />
```
{
    "prefix": "~",
    "token": "INSERT TOKEN HERE"
    "sqlpass": "INSERT PASSWORD HERE"
}
```

NodeJS Modules Needed: <br />
cheerio <br /> 
discord.js <br />
request <br />
mysql <br />
moment <br />
moment-timezone <br />
<br />
MySQL Database Info: <br />
Database Name: monkeybot <br />
<br />
Table Name: userinfo <br />
Columns: id, xp, league, region <br />
<br />
Table Name: mainchannel <br />
Columns: guildid, mainchannelid<br />