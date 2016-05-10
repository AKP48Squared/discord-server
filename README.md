This plugin allows AKP48Squared to connect to Discord servers.

# Installation

This plugin is included by default on new installations of AKP48Squared. No further installation is needed.

# Config

You'll need to add a new server to your configuration file for each Discord server you need to connect to. An example is shown below.

```
"servers": [
{
  "plugin": "discord",
  "config": {
    "token": "MTb0Mzr1MTI1ODl3OQI4NzA0.CRrPnQ.TcwwW-xsAA03VaX0PKuX31QQ", // bot token from Discord. See https://discordapp.com/developers/docs/intro for more info.
    "typingTimeout": 0.7, // how long to wait before AKP48 sends a message. Makes the typing indicator show up in Discord clients.
    "game": "with code" // what game AKP48 should be listed as playing.
  }
}
]
```

# Issues

If you come across any issues, you can report them on this GitHub repo [here](https://github.com/AKP48Squared/akp48-plugin-discord-server/issues).
