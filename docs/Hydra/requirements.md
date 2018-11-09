#Overview
Requirements are conditions that have to be met for the action to be triggered/for the button to be visible. There are a number of different requirements in the current version of Hydra. Here’s a list of the currently available ones.
#Compare
Compare is the most versatile but also the most complicated requirement to use. It compares strings and checks if they are equal. Strings can be placeholders(PlaceholderAPI – insert link here) which means that you can require a multitude of things, including things from other plugins. Below are a couple of examples for the “Compare”-requirement:

Example 1: Using the Placeholder Expansion “Server” you can require a certain amount of players to be online to activate something. If you set String A to %server_online%(placeholder from the “Server” expansion that shows amount of online players) and String B to 10, you’ll require exactly 10 players, no more, no less for the requirement to be met.
Example 2: Using the Placeholder Expansion “Player” you can require the player to be at a certain EXP level to activate something. If you set String A to %player_level%(placeholder from the “Player” expansion that shows the current level of the player) and set string B to 5, the player will have to have exactly 5 levels to meet the requirement.

#Flying
Checks if the player is flying. This does NOT check if fly mode is activated from a plugin like essentials. This checks if the player is flying right now meaning that he has doubleclicked on his jump-button and is now hovering in the air.

#Has Gamemode
Checks if the player is in a certain gamemode. Modes which you can check for include Survival, Adventure, Creative, Spectator.

#Require Item
Not yet written.

#Has Money
Uses vault(link) and a vault-compatible economy plugin to check if the players has a specific amount of money left in the bank. 

#Operator
Checks if the player is an ooperator”/op”). Good for close to vanilla experience servers who doesn’t have a permission plugin. 

#Permission
Checks if the player has a specific permission. Can not be used to check if the player is in a certain permission group. 

#Player Online
Checks if a specific player is online.

#Require Variable
Checks if a specific variable exists. 

#World Requirement
Checks if the player is in a specific world. Can be used on a bungeecord network to check which server the player is on by using ReWorld or Multiverse and renaming the worlds to unique names and then setting this requirement to match those names based on which server should have the action/button available. 
