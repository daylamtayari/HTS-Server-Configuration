# HTS-Server-Configuration


## Introduction:

This repository contains all of the plugins and configuration files used in the servers of the Hebdo Tournament Series.   
Practically all of the plugins and files are pre-configured save for a few tweaks which must be implemented.   

Tournaments are run using the [Get5 plugin by Splewis](https://github.com/splewis/get5) as the foundation and is operated via [PhlexPlexico's fork](https://github.com/PhlexPlexico/get5-web) of [Splewis's web panel for Get5](https://github.com/splewis/get5-web) (which alone is solely a proof of concept).   
It also utilizes the [Steamworks](https://forums.alliedmods.net/showthread.php?t=229556), [SM Jansson](https://forums.alliedmods.net/showthread.php?t=184604) and [System2](https://forums.alliedmods.net/showthread.php?t=146019) plugins in order to correctly run.   

## Pre-requisites:

Before installing this, please make sure you have the following:
- Your server is fully up to date.
- [Metamod](http://www.sourcemm.net/) installed.  
- [SourceMod](https://www.sourcemod.net/) installed.  
- You have a successfully installed and running web panel. I would recommend using [PhlexPlexico's guide](https://github.com/PhlexPlexico/get5-web/wiki/Installation) to install it (in my experience this guide does not work if you use a version of Ubuntu greater than 18.04) if you have not already.

## Installation: 

1. Download and extract the folder.
2. Drag the entire folder into your server's CS:GO folder.
3. Open the `get5.cfg` configuration file found at `/csgo/cfg/sourcemod/` and edit the hostname format on line 58 to include your server's name (or change it entirely).
4. (Optional) If you wish to edit the plugin's message prefix, go to the same file as above and edit the cvar at line 100.
5. Add your server to your web panel and you can start running games.

## Disclaimers:

**I am not liable for any errors, data losses or any issues whatsoever that can be caused by installing this.**

## Credits:

- [Sean Lewis (splewis)](https://github.com/splewis) for the Get5 plugin and the Get5 web panel.
- [PhlexPlexico](https://github.com/PhlexPlexico) for his functional fork of the Get5 Web Panel and his installation guide.
