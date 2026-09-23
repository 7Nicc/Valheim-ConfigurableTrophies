# Configurable Trophies

A lightweight Valheim mod created by **7Nicc** that allows you to easily adjust or increase the drop rates of creature trophies across all biomes.

## Features
- **Custom Drop Rates:** Overrides default vanilla trophy drop chances to a configurable percentage.
- **Default Balance:** Sets base trophy drop chance to **50%** (0.5) out of the box.
- **Server Compatible:** Works seamlessly on both client and dedicated server setups.

## Installation
1. Ensure **BepInEx for Valheim** is installed.
2. Place `ConfigurableTrophies.dll` into your `BepInEx/plugins/` directory (or install directly via Gale / Thunderstore Mod Manager).
3. Launch the game once to generate the configuration file.

## Configuration
To adjust the trophy drop rate, open `BepInEx/config/com.nicc.configurabletrophies.cfg` in a text editor:

- **`TrophyDropChance`**: Controls the drop chance for all creature trophies.
  - `0.0` = 0% drop chance (No trophy drops)
  - `0.5` = 50% drop chance (Default setting)
  - `1.0` = 100% drop chance (Guaranteed trophy drop)

*Note: For dedicated servers, ensure both the server and connecting clients have matching configuration files.*