# buddyload
Planned Project (already exists, needs some finetuning)

Being nice to a friend and still wan to know what's going on
<br />without him asking "Hey, can I use your premium account to download this one file?"

Supports all sites that have 1 TLD... not exactly planned to add more... but maybe at some very much later point... 
<br />it's also very easy for you to extend it yourself.

Example data structure in `buddyload.json`:

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
