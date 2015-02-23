
[Source](http://www.umluex.at/bilder/minecraft/mc_server_commands.html "Permalink to Minecraft Commandlist")

# Minecraft Commandlist



    /help [Page] - Shows a list of commands. 7 per page.
    /playerlist - Shows a list of players
    /reload - Reloads config
    /listbans [IP or bans] - Gives a list of bans
    /banip [Player] [Reason] - Bans the player's IP
    /unbanip [IP] - Unbans the IP
    /ban [Player] [Reason] - Bans the player
    /unban [Player] - Unbans the player
    /mute [Player] - Toggles mute on player.
    /tp [Player] - Teleports to player. Credits to Zet from SA
    /tphere [Player] - Teleports the player to you
    /kick [Player] [Reason] - Kicks player
    /item [ID] [Amount] [Player] - Gives items
    /kit [Kit] - Gives a kit. To get a list of kits type /kit
    /listwarps - Gives a list of available warps
    /home - Teleports you home
    /sethome - Sets your home
    /setspawn - Sets the spawn point to your position.
    /me [Message] - * hey0 says hi!
    /msg [Player] [Message] - Sends a message to player
    /spawn - Teleports you to spawn
    /warp [Warp] - Warps to the specified warp.
    /setwarp [Warp] - Sets the warp to your current position.
    /removewarp [Warp] - Removes the specified warp.
    /getpos - Displays your current position.
    /compass - Gives you a compass reading.
    /time [Time|day|night] - Changes time
    /lighter - Gives you a lighter for lighting furnaces
    /motd - Displays the MOTD
    /modify [player] [key] [value] - Type /modify for more info
    /whitelist [operation (add or remove)] [player]
    /reservelist [operation (add or remove)] [player]

     Selection commands:
    //wand - Gives you a wand that lets you define a cuboid region
    //pos1 - Set position one of the selection to the block you are in
    //pos2 - Set position two of the selection to the block you are in
    //hpos1 - Set position one of the selection to the block that you are looking at
    //hpos2 - Set position two of the selection to the block that you are looking at
    //chunk - Select all the blocks in the chunk that you are in
    //expand - Expand your selection in any direction
    //contract - Contract your selection
    //size - Find out how big your selection is
    //count - Get the count of a certain block in the selection
    //distr - Get the block distribution in the region

     Clipboard commands:
    //copy - Copy to your clipboard
    //cut - Copy and delete
    //paste - Paste your selection
    //pasteair - Paste, air included
    //rotate - Rotate your clipboard
    //load - Load a .schematic
    //save - Save a .schematic
    //clearclipboard

     History commands:
    //undo
    //redo
    //clearhistory

     Region operations:
    //set - Set all the blocks inside a region to a block type, OR to a definable random mix of blocks (i.e only 1% diamond ore)
    //stack - Stack the region (i.e. repeat a section of a bridge)
    //stackair - Also copies air
    //move - Move the region
    //moveair - Also moves air
    //outline - Draw faces
    //walls - Draw walls
    //replace - Replace one block type with another, OR several block types with another, OR replace non-air blocks with another
    /replacenear - Shortcut //replace that works on nearby blocks
    //overlay - Overlay a block over the selected region
    //smooth - Smooth the terrain in the region

     Point operations:
    //fill - Fill holes with something
    //drain - Drains water and lava pools
    //cyl - Generate filled cylinders
    //hcyl - Generate hollow cylinders
    //sphere - Generate spheres
    //hsphere - Generate hollow spheres
    /fixwater - Level water and turns flowing water into stationary water
    /fixlava - Level lava and turns flowing lava into stationary lava
    /removeabove - Remove blocks directly above
    /removebelow - Remove blocks directly below
    /removenear - Remove blocks near you of a certain type (i.e. TNT)
    /forestgen - Generate a forest (with Notch's tree algorithm)
    /pinegen - Generate a pine tree forest
    /snow - Generate snow cover and freeze over lakes near you
    /butcher - Kill nearby mobs

     Restoring from backups:
    /listsnapshots - List the backups available to use
    //use - Select the backup to use
    //restore - Restore the selection region from a backup

     Tools:
    // or /, - Toggle super pickaxe mode to remove any block instantly
    //mode - Super-super pickaxe modes with area and recursive effects
    //tool - Lets you use extra tools, like insta-tree!
    /unstuck - Frees you if you are stuck inside some blocks
    /ascend - Go up to the level above you
    /descend - Go down a level
    /ceil - Get access to the ceiling above you
    /thru - Go through the wall that you are looking at
    /up - Go upwards some distance
    /jumpto - Go to the block that you are looking at
    /chunkinfo - Get the coordinates and path of the chunk that you are in currently in
    /listchunks - Get a list of chunks
    /delchunks - Generate a shell script to delete chunks
    /ex - Fire extinguisher

     Per-player preferences:
    //limit - Set a maximum block change limit for operations
    /toggleeditwand - Toggles use of the edit wand
    /toggleplace - Rather than use your feet, use position 1 for point commands

     Commands:
    /noclip - Movement spell. Allows flight and walking through walls.
              Look in the direction you wish to travel (even up or down), then move in any direction.
    /gravitygun - Wand spell. Shoot down floating islands.
    /Bubble - Movement spell. Surrounds you with a bubble of glass. Great for undersea exploration!
    /LightSaber - Wand spell. Instantly destroys any block.
    /ConeOfCold - Wand spell. Creates a blast of snow and ice.
    /SandBlaster - Wand spell. Drops a huge ball of sand!
    /miraclegro - Special spell. Makes planted saplings grow tall instantly.
    /familiar - Special spell. Summons a loyal animal familiar!
    /flowerchild - Movement spell. Makes flowers grow nearby.
    /hover - Movement spell. Places a temporary water block at your feet, creating a "hover" effect.
    /frozone - Wand spell. Creates temporary magical ice bridges.
    /frost - Movement spell. Temporarily freezes nearby blocks.
    /Heat - Movement spell. Temporarily melt nearby snow and ice.
    /magicladder - Wand spell. Create instant ladders many blocks tall!
    /rain - Movement spell. Temporarily places a flowing block of water over your head.
    /xray - Movement spell. Temporarily turns nearby stone into glass. Reverts to stone when harvested.
    /midastouch - Wand spell. Temporarily turns trees into gold.
    /magictorch - Movement spell. Creates a torch that magically follows you.
    /eviltorch - Movement spell. Creates a redstone torch that magically follows you.
    /johnhenry - Special spell. place long lines of rain on flat ground when one rail block is placed.
    /magictrick - Reports version information

     The wand
    The "wand" is really just the stick item. It is usually activated in one of two ways:
    Swing: Left click empty air (no block targeted)
    Target: Right click on a block

    /magiccarpet to toggle the carpet.

     Book Reading:
    Just right click a bookshelf. It will load from a craftbook-books.txt file. You may edit that file
    and add your own lines or replace it altogether. Each "book" goes on its own line. The file can be
    as big as you want it to be -- CraftBook never loads the entire thing into memory.

     Gate Toggle:
    Make a wall sign near a fence gate with the second line as [Gate]. To toggle the gate, just right
    click the sign.

     Elevator:
    Make it easy to go from level to level with this nifty elevator. Just make a sign with the second
    line as [Lift Up] or [Lift Down] and right click it to move between levels. Note that there must be
    a sign directly above or below the sign you right click on (depending on which way you want to go)
    in order for the elevator to work. Use [Lift] on the second line of a sign if you just need a
    placeholder for that purpose. The first line of the sign can be used to say the floor name (it will
    be printed to chat).

     Area Light Switch:
    This will toggle on the lights in the area on/off (about 10 units away, 5 units up/down). Just make
    a wall sign with the second line as [|] and have a torch above the sign.

     Apple Trees:
    Every time you destroy leaves, you may get an apple dropped for you to pick up. This chance can be
    adjusted inside craftbook.properties (the file is created when you first run CraftBook). Use a
    number between 0 and 100, with 100 being a 100% chance.

     Bookshelf Drops:
    Every time you destroy a bookshelf, you will get a bookshelf item.  
