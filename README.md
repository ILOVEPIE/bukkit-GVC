![*Gliby's Voicechat Mod*](https://dl.dropboxusercontent.com/u/77796356/logo.png)
Players will need [Gliby's Voice Chat](http://www.minecraftforum.net/topic/1960307-162-forge-glibys-voice-chat-mod-speak-ingame-communicate-with-other-players-over-voice-bukkit-server-support-lan-support/#entry24135256).

Major update incoming! 
==================

This plugin makes your server to *compatible* with *Gliby's Voice Chat* mod

What does it do?
----------------------
* This plugin will allow people with *Gliby's Voice Chat* to speak while in game.
* Provides developers with a library of classes that allow for voice chat triggered game mechanics.

What are the requirements to use the plugin?
------------------------------------------------------------
* SERVER: Only this plugin.
* CLIENT: Forge Client, a microphone, and Gliby's Voice Chat mod for Forge.

Internet Minimum Requirements:
--------------------------------------------
* SERVER: 10 players = ~160kb/s DOWNLOAD *and* UPLOAD.
* CLIENT: At least 25kb/s upload.


Standard Commands
----------------------------
* /mute <player> - Mutes players, if player already muted then unmutes.
* /toggleglobalchat - Toggles globat chat for you, everyone in all worlds will hear what you say!
* /listmuted - Lists all muted online players.[/list]

WorldGuard Commands
--------------------------------
* /addchatregion <world-guard region> - Add's chat region(Region Chat).
* /removechatregion  <worldguard-region> - Remove's chat region(Region Chat)![/list]

Permissions
----------------
    gvc.mute
    gvc.talk
    gvc.addchatregion
    gvc.removechatregion
    gvc.allowchatregion
    gvc.toggleglobalchat
    gvc.listmuted.
    gvc.listregions
    gvc.*

*Permissions Pastebin*: [http://pastebin.com/r6xHjTPp](http://pastebin.com/r6xHjTPp).

Permission Voice Plates
--------------------------------
![permission plates](https://dl.dropboxusercontent.com/u/77796356/permission-plates.png)

What are voice plates?
------------------------------
They are the plates that show up to other players when you speak, plates are different for each group with a certain permission. 

Permission Descriptions
--------------------------------
    gvc.mute - Command Permission used to mute player.
    gvc.talk - Allows you to speak (Not used for muting!).
    gvc.addchatregion - CommandPermission used to remove WorldGuard chat region.
    gvc.removechatregion - CommandPermission used to remove WorldGuard chat region.
    gvc.allowchatregion - Permission used to allow players to talk in a chat region!.
    gvc.toggleglobalchat - Command Permission used to allow global chat.
    gvc.listmuted - Command Permission used to list all muted players.
    gvc.* Gives access to all GVC permissions/commands(except priorities).
    gvc.listregions - Command Permission used to list all GVC regions.

Configuration
------------------

to edit the configuration start your server once then go to "plugins/GVC/config.properties", you will find

* DEFAULT_DISTANCE - Default 3D Audio Distance. (Recommended value is 63, 64 and above cause client crashes)
* REQUIRE-GVC - If true then players will be kicked if they do not have *Gliby's Voice Chat Mod* on their client, if false then anyone can join.
