# buddyload
Planned Project (already exists, needs some finetuning)

Being nice to a friend and still wan to know what's going on
<br />without him asking "Hey, can I use your premium account to download this one file?"

Supports all sites that have .com or .org as a TLD... you can request to add more in [Issues](https://github.com/spookyahell/buddyload/issues)

### Prerequisites
- Telegram Bot token
- Device that will allow you to open a TCP port with python3.6+ and that runs 24/7 (a server is usually good for that)
- At least one premium account to make any sense out of this
- aria2c (for the downloading)

Data structure in `buddyload.json` (with uptobox & 1fichier as example accounts):

    {
      "port": "$PORTNUMBER",
      "accounts": [
        {
          "name": "uptobox",
          "xfss": "$COOKIE_VALUE"
        },
        {
          "name": "1fichier",
          "SID": "$COOKIE_VALUE"
        }
      ],
      "msg": "Hi, bud, how are you today?"
    }
