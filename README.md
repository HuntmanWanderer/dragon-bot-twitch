Dragon Bot
==========
The Dragon Bot is a [Twitch](https://twitch.tv/ "Twitch.tv") bot that allows other developers to make plugins and expand it to make it better,
this bot was created with the ideas that [Spigot](https://www.spigotmc.org/ "Spigot's Webpage") was created under. To allow the users to make their
own addons to it to make it fit their needs.

Official Plugins
----------------
These are open source plugins that either I have worked on, or that I've worked closely on with the developers.  
  
- [Dragon Bot Essentials](https://github.com/Dragovorn/essentials "Dragon Bot Essentials' Github") - A plugin aimed at adding 'Essential' functionality to the Dragon Bot

Installation
------------
The only installation process for the bot is to download the latest full release (But Snapshots might have some important bugfixes)  
If you are on **Linux** you might have to install the JavaFX libraries for the newer versions to work because we've moved from swing
to JavaFX. You can install it by executing
```
sudo apt install openjfx
```

Development
-----------
Now I just need to stop being lazy and write some tutorials on plugin development, right now just look at the essentials plugin for references.

**There currently isn't a maven repo for the Dragon Bot's api**  
The above being said, that means that you have to download the Dragon Bot inorder to write plugins for it.

**Also let it be known that I like changing the API a lot which could end up in some versions breaking plugins when it is first released. I will try my darnedest to keep the wiki up to date and to release detailed change-logs about what all got changed.**

Deprecation Policy
------------------
I like to clean deprecated things out as quickly as possible, sometimes something that is not deprecated might get removed too. It's kinda the lifecycle as I try to keep things as shiney as possible and optimize every inefficiency I am capable of spotting.

History
-------
- Use of certain aspects of [BungeeCord](https://www.spigotmc.org/ "BungeeCord's Webpage") for plugin specific schedulers and recursive dependency loading.
- Fork of [PIRCBot](http://www.jibble.org/pircbot.php "PIRCBot's Webpage").