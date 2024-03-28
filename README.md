# GMKbot

BotURL: t.me/GmDevOpsKbot
Build the bot:
```
go build -ldflags "-X="github.com/GlibMartynenko/gmkbot/cmd.appVersion=v1.0.1
```
Makre sure that your Telegram token is assigned to this env variabel **TELE_TOKEN**
To run the bot use the follwing command:
```
/gmkbot go
```