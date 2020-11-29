Download
-------------
https://www.spigotmc.org/resources/supervanish-be-invisible.1331/

Credits
--------------
[NOTE] THIS PLUGIN IS NOT MADE BY ME!

CREDITS TO LeonMangler FOR CREATING THIS PLUGIN.

YOU CAN CHECK OUT THE OWNER'S PAGE HERE: https://github.com/LeonMangler


Minecraft Version
--------------
**Compatible On Version 1.7,1.8,1.9,1.10,1.11,1.12,1.13,1.14,1.15,1.16**

SuperVanish -- A Spigot Plugin
--------------

This is an advanced vanish-plugin which makes other players think that you're not on the server.
Great for catching griefers or testing out new moderators!
Don't forget to install ProtocolLib first if you want to use the serverlist, action bar or silent chest features.
1.16: Important - install the latest ProtocolLib dev build as described in ProtocolLib's resource description!

Features
--------------
Invisible players are completely invisible
Hides invisible players in the playerlist [Tab]
Adjusts the amount of online players in the serverlist (Requires ProtocolLib)​
For players who are allowed to see a vanished player only the vanished player's head is visible and the vanished player's name is italic gray in the tablist (can be turned off)
Layered permissions which allow you to configure who can see who precisely

Shows action bars to invisible players (Requires ProtocolLib)
You can change nearly every message from this plugin in messages.yml
Invisible players are still invisible after join/quit
Invisible players are still invisible after a reload/restart
Invisible players cannot pick up items
Disables the ''normal'' join/leave messages of hidden players
Broadcasts a fake join/leave message on vanish and/or reappear
Disables damage for invisible players
Hides items in the hand of invisible players
Hides the armour of invisible players
You can reload the configuration in-game
Invisible players can open chests silently (Requires ProtocolLib)
Invisible players can't trigger pressure plates
Invisible players can fly even if they are in survival mode
Invisible players can't block the placement of blocks
Invisible players can't block arrows (but get teleported two blocks up)

Commands And Permission 
---------------
[...] = Optional; <...> = Required
/sv help - Shows a convenient help page with a list of commands
/sv [on|off] - Hides/shows you - sv.use [.levelX]
/sv [on|off] <player> - Hides/shows an other player - sv.others
/sv reload - Reloads the config files - sv.reload
/sv list - Shows a list of invisible players - sv.list
/sv login - Broadcasts a login message - sv.login
/sv logout - Broadcasts a logout message - sv.logout
/sv recreatefiles [confirm|force] - recreates outdated config files - sv.recreatefiles
/sv tipu - Toggles picking up items per player - sv.toggleitems
/sv stacktrace - Logs information for reporting an issue
Other notable permissions:
sv.see [.levelX] - Players with this permission can see invisible players (if it's enabled in the config)
sv.keepfly - Players without this permission will lose the ability to fly when they reappear and aren't in creative mode
sv.notoggle - The vanish state of players with this permission cannot be changed by other players
  
Support
--------------
https://www.spigotmc.org/threads/supervanish-be-invisible.31309/
