# List of functions & usage

### Send a title with subtitle

```showTitle("TITLE", "SUBTITLE", player)```

*Want to make it an argument? Do it like this:*

```showTitle(arg-1, arg-2, player)```

### Send an actionbar message

```showActionbar("MESSAGE", player)```

### Set the world time

```setTime("DAY/NIGHT")```

### Teleport a player to another player

```doTeleport(PLAYER, PLAYER)```

*eg: getTeleport(player, Notch), this will teleport the executor to a player called "Notch"*

### Get number of online players

```getOnline(player)```

### Get names of online players

```getOnlineNames(player)```

# CYOM *(requires CreateYourOwnMenu plugin)*

### Open a menu

```cyomMenuOpen("MENU", player)```

### Edit a menu

```cyomMenuEdit("MENU", player)```

# Vault *(requires Vault plugin)*

### Show player's balance

```vaultShowBalance(player)```

### Add money to player's balance

```vaultAddBalance(AMOUNT, player)```

### Remove money from player's balance

```vaultRemoveBalance(AMOUNT, player)```

### Set a player's balance

```vaultSetBalance(AMOUNT, player)```

# Multiverse *(requires Multiverse plugin)*

### Create world

```mvCreateWorld("WORLDNAME", "TYPE", "PRESET")```*Leave "PRESET" blank for normal world*

### Delete world

```mvDeleteWorld("WORLDNAME")```*

### TP to a world

```mvTpWorld("WORLDNAME", player)```

# Chat Manager *(requires Chat Manager script)*

### Clear Chat

```cmClear("REASON", player)```

### Mute Chat

```cmMute("REASON", player)```

### Unmute Chat

```cmUnmute("REASON", player)```

### Chat Announcement

```cmAnnounce("ANNOUNCEMENT", player)```

### Chat Countdown

```cmCountdown("SECONDS", player)```

### Chat Fake Join/Leave 

```cmFake("JOIN/LEAVE", "PLAYER NAME", player)```
