# KeepWifeHappy

Sends a text message to my wife if I am still logged into my computer.

```osascript sendMessage.applescript 1234567890 "This is a message."```

Trigger this via cron every 15 minutes during the 5pm hour.

```*/15 17 * * * osascript sendMessage.applescript 1234567890 "I am still at the office :("
