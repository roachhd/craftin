== Summary of commands ==

The table below summarizes available commands. Click a column heading to sort by that column.

{| class="sortable wikitable" style="text-align:center;"
|+ Summary of Commands
! style="text-align:left;" | Command
! style="text-align:left;" | Description
! {{Tooltip|Op Only|Commands only usable by operators}}
! {{Tooltip|MP Only|Commands only usable in multiplayer}}
! {{Tooltip|Blocks|Commands which modify or query blocks}}
! {{Tooltip|Entities|Commands which modify or query entities (mobs, items, etc.)}}
! {{Tooltip|Players|Commands which modify or query players}}
! {{Tooltip|World|Commands which modify or query the world}}
|-
| style="text-align:left;" | {{cmd|achievement}}
| style="text-align:left;" | Gives or removes an achievement from a player.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|ban}}
| style="text-align:left;" | Adds player to banlist.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|ban-ip}}
| style="text-align:left;" | Adds IP address to banlist.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|banlist}}
| style="text-align:left;" | Displays banlist.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|blockdata}}
| style="text-align:left;" | Modifies the data tag of a block.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|yes|Blocks}} || {{tc|-}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|clear}}
| style="text-align:left;" | Clears items from player inventory.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|clone}}
| style="text-align:left;" | Copies blocks from one place to another.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|yes|Blocks}} || {{tc|-}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|debug}}
| style="text-align:left;" | Starts or stops a debugging session.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|defaultgamemode}}
| style="text-align:left;" | Sets the default [[game mode]].
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|deop}}
| style="text-align:left;" | Revoke operator status from a player.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|difficulty}}
| style="text-align:left;" | Sets the difficulty level.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|effect}}
| style="text-align:left;" | Add or remove [[status effect]]s.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Entities}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|enchant}}
| style="text-align:left;" | Enchants a player item.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|entitydata}}
| style="text-align:left;" | Modifies the data tag of an entity.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Entities}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|execute}}
| style="text-align:left;" | Executes another command.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|fill}}
| style="text-align:left;" | Fills a region with a specific block.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|yes|Blocks}} || {{tc|-}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|gamemode}}
| style="text-align:left;" | Sets a player's [[game mode]].
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|gamerule}}
| style="text-align:left;" | Sets or queries a game rule value.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|give}}
| style="text-align:left;" | Gives an item to a player.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|help}}
| style="text-align:left;" | Provides help for commands.
| {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|kick}}
| style="text-align:left;" | Kicks a player off a server.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|kill}}
| style="text-align:left;" | Kills entities (players, mobs, items, etc.).
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Entities}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|list}}
| style="text-align:left;" | Lists players on the server.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|me}}
| style="text-align:left;" | Displays a message about yourself.
| {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|op}}
| style="text-align:left;" | Grants operator status to a player.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|pardon}}
| style="text-align:left;" | Removes entries from the banlist.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|particle}}
| style="text-align:left;" | Creates particles.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|playsound}}
| style="text-align:left;" | Plays a sound.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|publish}}
| style="text-align:left;" | Opens single-player world to local network.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|replaceitem}}
| style="text-align:left;" | Replaces items in inventories.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|yes|Blocks}} || {{tc|yes|Entities}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|save-all}}
| style="text-align:left;" | Saves the server to disk.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|save-off}}
| style="text-align:left;" | Disables automatic server saves.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|save-on}}
| style="text-align:left;" | Enables automatic server saves.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|say}}
| style="text-align:left;" | Displays a message to multiple players.
| {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|scoreboard}}
| style="text-align:left;" | Manages objectives, players, and teams.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Entities}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|seed}}
| style="text-align:left;" | Displays the [[world seed]].
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|setblock}}
| style="text-align:left;" | Changes a block to another block.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|yes|Blocks}} || {{tc|-}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|setidletimeout}}
| style="text-align:left;" | Sets the time before idle players are kicked.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|setworldspawn}}
| style="text-align:left;" | Sets the [[Spawn#Player spawning|world spawn]].
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|spawnpoint}}
| style="text-align:left;" | Sets the spawn point for a player.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|spreadplayers}}
| style="text-align:left;" | Teleports entities to random locations.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Entities}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|stats}}
| style="text-align:left;" | Update objectives from command results.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|yes|Blocks}} || {{tc|yes|Entities}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|stop}}
| style="text-align:left;" | Stops a server.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|summon}}
| style="text-align:left;" | Summons an entity.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Entities}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|tell}}
| style="text-align:left;" | Displays a private message to other players.
| {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|tellraw}}
| style="text-align:left;" | Displays a JSON message to players.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|testfor}}
| style="text-align:left;" | Counts entities matching specified conditions.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Entities}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|testforblock}}
| style="text-align:left;" | Tests whether a block is in a location.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|yes|Blocks}} || {{tc|-}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|testforblocks}}
| style="text-align:left;" | Tests whether the blocks in two regions match.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|yes|Blocks}} || {{tc|-}} || {{tc|-}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|time}}
| style="text-align:left;" | Changes or queries the world's game time.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|title}}
| style="text-align:left;" | Manages screen titles.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|toggledownfall}}
| style="text-align:left;" | Toggles the weather.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|tp}}
| style="text-align:left;" | Teleports entities.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Entities}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|trigger}}
| style="text-align:left;" | Sets a trigger to be activated.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|weather}}
| style="text-align:left;" | Sets the weather.
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|whitelist}}
| style="text-align:left;" | Manages server whitelist.
| {{tc|yes|Op}} || {{tc|yes|MP}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|-
| style="text-align:left;" | {{cmd|worldborder}}
| style="text-align:left;" | Manages the [[world border]].
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|World}}
|-
| style="text-align:left;" | {{cmd|xp}}
| style="text-align:left;" | Adds or removes player [[experience]].
| {{tc|yes|Op}} || {{tc|-}} || {{tc|-}} || {{tc|-}} || {{tc|yes|Players}} || {{tc|-}}
|}
