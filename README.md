# csgo-config
Personal autoexec configuration for Counter-Strike: Global Offensive

# Features
* Personal binds. If you want to use it for yourself, read the config and edit your binds accordingly.
    * jump bind
    * binds for different grenade types
* When pulling out a grenade,
    * Automatically use a large crosshair for more presice grenade lineups. And switch back to my default crosshair when the grenade is thrown or a knife/gun is pulled out.
    * Automatically trigger `cl_righthand 1`, and back to `cl_righthand 0` when thrown or using a knife/gun. Since a lot of grenade lineups use the viewmodel as a reference.
* "Practice mode" setting.
* Demo-viewing modes.



# Installation
1. Locate CS:GO local files.
2. Copy the files to your `Counter-Strike Global Offensive\csgo\cfg` local directory.
3. Add `+exec autoexec.cfg` to CS:GO's [launch options](https://support.steampowered.com/kb_article.php?s=3b07c7f6cbf07cedba1afb7a5d2e8b9d&ref=1040-JWMT-2947).

# Usage
1. Demo-viewing mode
    1. From the main menu, click the watch tab and select any of your downloaded games. Or press `Shift+F2` to access the demoplayer UI and load any downloaded demo file. (From sites like hltv.org, for example)
    2. On the developer console, type `exec demobinds` for an easier demo-viewing experience. Read `demobinds.cfg` to see the commands. Edit them accordingly.
    3. Some of the binds include fastforward and slow-motion when holding specific keys.
2. Practice mode
    1. From the main menu, type `map [map_name];comp` example: `map de_dust2;comp`
    2. When the map loads, type `prac` to load the practice server config.
    3. Practice config includes
        * Trying "vanilla" version of knives. Read `giveknife.cfg` for specific commands and binds.
        * Infinite ammo
        * Enabled buying anywhere on the map. Not just the buy zones at spawns.
