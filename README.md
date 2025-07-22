# CounterStrikeSharp & MetaMod Installer and Updater

### Prerequisites
* Ubuntu/Debian
* WGET
* cURL
* unZip
### Info
This script install and update files from CounterStrikeSharp and MetaMod. 

### Setup
To run the script you need to modify the following
```
WORKING="cs_mm_files"  # This is the directory of the install or update files
CS2_WORKING_DIR="/usr/local/steam/csgo/game/csgo"  # This is the directory path of "gameinfo.gi" file
```

This is how you set your server install path. You need to go up to the point on the directory of the csgo directory. So if you installed your server with [Linux Game Server Managers](https://gameservermanagers.com/) usually the path is serverfiles/csgo from the directory of the install.

Please note that the paths for your installs should be full paths so that it doesn't matter where you place the scripts.

### Why?
I wrote this script because the counterstrikesharp or metamod files are often updated to be usable with counter-strike 2.

## Authors
* **lovasatt** - Author 2025
* **Kenny Lindelof** - *Mmmmm code*

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Links 
* [CounterStrikeSharp](https://docs.cssharp.dev/)
* [MetaMod](https://www.metamodsource.net/)
