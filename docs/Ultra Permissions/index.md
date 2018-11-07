# Overview

## What is Ultra Permissions?

UltraPermissions is a next level permissions system that can be fully controlled via GUI's ingame. It is able to suggest you permissions based on installed plugins so you no longer have to search the internet for those! 

## Commands

All of these commands can only be used either with the console or as a *superadmin*.

* `/uperms` for the GUI

Other Commands:
  * `/upc addGroup <Player> <GroupName> (Time 3h, 10d)`
  * `/upc addGroupPermission <Group> <Permission>` *(Options)*
  * `/upc addPlayerPermission <Player> <Permission>` *(Options)*
  * `/upc addSuperadmin <Player>`
  * `/upc removeGroup <Player> <GroupName>`
  * `/upc removeGroupPermission <Group> <Permission>`
  * `/upc removePlayerPermission <Player> <Permission>`
  * `/upc removeSuperadmin <Player>`
  * `/upc transfer (From <File / MySQL>) (To <File / MySQL>)`

*(Options)* means that you can add additional options seen below. You seperate each option with a space.

 - Time ex. `1d 4h 3m` (d = day, h = hour, m = minute)
 - `bungee` (Will be applied as a Bungee Permission)
 - `local` (Will be applied only on the current Server)

## Placeholders

PlaceholderAPI Placeholders:

* `%uperms_prefix%` Player Prefix or Prefix of 1. Group
* `%uperms_suffix%` Player Suffix or Suffix of 1. Group
* `%uperms_rank%` Group Name of 1. Group
* `%uperms_prefixes%` Replaced with player prefix & group prefixes
* `%uperms_suffixes%` Replaced with player suffix & group suffixes

For the MvdwPlaceholderAPI use `{ .. }` instead of `% .. %`

## Permission Database

With thousands of Permissions, Ultra Permissions has a fairly large permission database to show you all important permissions at a glance. We, as a community added almost all well known plugins to the database. And if a plugin is not in the database, Ultra Permissions tries its best to extract those permissions from the plugin Jar File instead.

**How to contribute:**

The Permission Database is hosted on [Github](https://github.com/TechsCode/UltraPermissionsDatabase) and you are welcome to contribute to it. An instruction is available there as well!

## Vault Support

Ultra Permissions supports the Vault Chat Hook as well as the Permissions Hook. You can use it with any other plugin thats Vault compatible. Some vault features may be limited due to the different behaviour Ultra Permissions has compared to other Permissions Plugins.

## Need Help?

Do you need help on something that is not (yet) on the wiki? Come join our discord here: [Tech's Plugin Support Discord](https://discord.gg/GmuPTqb)
