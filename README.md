# Stick Gaming Pluto T6ZM V2.0 Bleed-out Bar
Add a bleed-out bar when you are down and tell you how long you have to live.
Kinda like Bo4 and CW bleed-out bar

## Bleedout Bar V2.0
![](https://media.discordapp.net/attachments/758863563623890965/952946850976137316/unknown.png?width=1249&height=702)

# Features
-	**Bleedout Bar V2.0**
	- When players go down a progress bar a countdown will display how long to until you bleed out  
    - Custom Dvar for Bleedout Timer and revive trigger
    - New Clean Bleedout Bar
    - 100% Bug-free (Compared to V1.0)
    - an overhaul of 95% of the script

## Requirements
- Have a copy of Black Ops 2 with all DLC.
- Have the latest version of Project [Plutonium](https://plutonium.pw/)
- Have a copy of the compiler from [Plutonium forum](https://plutonium.pw/docs/modding/loading-mods/#t6), in the GSC Example Toolkit

## Config
| Dvar | Description |
| ------ | ------ |
| bleedout_timer | Change how long you want your player to be in the last stand before dying(Default 45, 2min 120, 3min 180) |
| revive_trigger | How far away do you want the player to be able to revive a down player (Default 75, 128 allow you to get quad feed to revive and allow the players to walk around the player) |


## Installation
- Compile the script or for a pre-compile go look in our [release](https://github.com/Stick-Gaming/pluto-t6zm-bleedout-bar/releases) 

- Copy the compiled files to your `AppData/Local/Plutonium/storage/t6/scripts/zm` folder

- One copy you will need to rename each script to remove -complied from their name

- In your Server.cfg file add this to the bottom
```
set bleedout_timer 45 // Change how long you want your player to be in the last stand before dying(Default 45, 2min 120, 3min 180)
set revive_trigger 75 // how far away do you want the player to be able to revive a down player (Default 75, 128 allow you to get quad feed revive and allow the players to walk around the player)
```


## Contributors
-	[Nathan3197](https://twitter.com/nathan3197) - Owner/developer
-   The hundreds of people who tested this on our servers
