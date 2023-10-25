<div align="center">
<h1>IRC Bash :speech_balloon:</h1>
<p>A super simple IRC client written in pure Bash v4.2+</p>
<a href='#'><img src="https://img.shields.io/badge/Made%20with-BASH-&?style=flat-square&labelColor=232329&color=4ca824&logo=gnu-bash"/></a>
<a href='#'><img src="https://img.shields.io/badge/Maintained%3F-Yes-green.svg?style=flat-square&labelColor=232329&color=5277C3"></img></a>
<br/>

<a href='#'><img src="https://img.shields.io/github/size/opensource-force/snake/src/snake.nim?branch=main&color=%231DBF73&label=Size&logo=files&logoColor=%231DBF73&style=flat-square&labelColor=232329"/></a>
<br/>
<a href="https://discord.gg/W4mQqNnfSq">
<img src="https://discordapp.com/api/guilds/913584348937207839/widget.png?style=shield"/></a>
</div>

## Acquisition
Download `irc-bash`
```bash
git clone https://github.com/wick3dr0se/irc-bash; cd irc-bash/
```

---

## Execution
Execute client from within downloaded directory, optionally specifying an IP address and/or port to connect to. If IP is not specified, port becomes first argument 
```bash
bash irc-bash [ip] [port]
```

Or
```bash
chomod u+x irc-bash
./irc-bash [port]
```

## Usage
The client request password first, parses environment variables to determine nickname, username and hostname automatically

```bash
/pass, PASS  ...  Update server password
/nick, NICK  ...  Update server nickname
/join, JOIN  ...  Join server channel(s)
/msg, PRIVMSG  ...  Message a nickname or channel
```

## Contributing
Make a change; Submit that PR with a relevant message, e.g. `git commit -m 'issus fix #3'`
