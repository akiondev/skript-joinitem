# JoinItem Skript 
[![Discord](https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/v4umqdd7Aj)

A simple and flexible Skript for Minecraft servers that gives players a custom item when they join. The item executes the `/menu` command on click and is intended to act as a server menu shortcut. This script is ideal for use with GUI plugins like ChestCommands or DeluxeMenus.

## Requirements

- Minecraft server with the [Skript plugin](https://github.com/SkriptLang/Skript)
- Skript version: 2.12.0 (tested)
- A GUI plugin that handles the `/menu` command

## Features

- Automatically gives players a menu item in hotbar slot 8 when they:
  - Join the server
  - Respawn
  - Change world (e.g. Multiverse support)
- Prevents the item from being:
  - Dropped on death
  - Manually dropped
  - Moved in the inventory
- Restores the item if missing or renamed
- Triggers `/menu` on right- or left-click with the item

## Installation

1. Download the file `joinitem.sk`.
2. Place it in your server's `plugins/Skript/scripts/` folder.
3. Run the command `/skript reload joinitem` in-game or via console.
4. Make sure your GUI plugin is configured to open a menu via `/menu`.

## Support

For questions or support, please contact:  
[akiondev on Discord](https://discord.gg/v4umqdd7Aj)

## Attribution

This script was written for use with the [Skript](https://github.com/SkriptLang/Skript) plugin.  
All credit for the Skript language and its development goes to the SkriptLang team.

## License

This script is open source and may be freely used, modified, and shared. Attribution is appreciated but not required.
