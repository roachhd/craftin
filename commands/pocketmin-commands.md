#PocketMine Server Commands


## Plugin Commands

###### More Commands 
```
Commands:
 - gms usage: /gms | Changes your gamemode to survival
 - gmc usage: /gmc | Changes your gamemode to creative
 - gma usage: /gma | Changes your gamemode to adventure
 - gmspc usage: /gmspc | Changes your gamemode to spectator
 Note:not sure how spectator works in Pocket Edition, but you may find this useful.
 - slay usage: /slay <player> | Kills the specified player
 - heal usage: /heal [player] | This heals you, or, if specified, another player.
 - mute usage: /mute <player> | This will mute the specified player.
 - unmute usage: /unmute <player> | Unmutes the specified player.
 - freeze usage: /freeze <player>
 Freezes a player so that they can't move. When you're frozen, it tends to have graphical glitches or make you stuck in the ground (for me its both); I believe this is just a bug in PocketMine-MP. In future updates to PocketMine-MP it should be fixed.
 - unfreeze usage: /unfreeze <player> | Unfreezes the specified player.
```


##### Simple Macros
```
Commands:
 /macro start - start recording a macro
 /macro stop <name|NG> - stop and save a macro with the specified name, or discard if NG is given instead
 /macro pause - pause recording
 /macro resume - resume recording
 /macro run <name> - run the macro <name>
 /macro sudo <name> <player> [-op] - sudo <player> to run the macro <name>, and allow him to run those commands that he doesn't have permission to if "-op" is given at the end.
```

##### Spleef Arena
```
Player Commands: 
------------------------------------------------------------------------------------------------
"/spleef stats" -- show number of players inside Sleef Arena
"/spleef home" -- send player to spleef home world 
"/spleef lobby" -- send player to server lobby world 

Admin Commands: 
------------------------------------------------------------------------------------------------
"/spleef create" - re-build spleef arena from scratch
"/spleef reset" - reset arena to fix any broken parts 
"/spleef blockon" - enable display of block location 
"/spleef blockoff" - disable display of block location

** setup button
"/speef setbuttonjoin" --setup join button location
"/speef setbuttonstart" --setup start button location

** setup sign
"/speef setsignjoin" --setup join sign location
"/speef setsignstart" --setup start sign location
"/speef setsignstats" --setup view stats sign location
"/speef setsignhome" --setup sign for spleef home 
"/speef setsignlobby" --setup sign for server lobby

**setup postion
"/speef setposhome" --setup position for spleef home world
"/speef setposlobby" --setup position for server lobby world
"/speef setposplayenter" --setup postion for player landing in arena
```


