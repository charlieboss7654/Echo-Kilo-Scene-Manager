# EKS Scene Manager

A standalone scene/traffic management tool with a custom NUI menu.

## Requirements
- ox_lib

## Install
1. Drag `EKS_SceneManager` into your server `resources` folder.
2. Ensure ox_lib is started before this resource.
3. Add to your server.cfg:
   - `ensure ox_lib`
   - `ensure EKS_SceneManager`

## Use
- Command: `/scenemanager`
- Keybind: `F5` (changeable in Settings > Key Bindings > FiveM)

## Features
- Stop Traffic (radius)
- Set Traffic Speed (speed + radius)
- Timed Traffic Zone (speed + radius + seconds)
- Secure Zone (peds flee, NPC vehicles deleted)
- Delete Nearest Zone / Delete All Zones (your zones only)
- Lane Management (toggle road nodes open/closed)
- Traffic Control Equipment props (hologram placement)
- Scene Control Equipment props (hologram placement)
- Zone radius blips on map

## Config
Edit `shared/config.lua` to adjust defaults, keybinds, props, and lane settings.

## Support
For help or bug reports, join our Discord and open a support ticket:
https://discord.gg/busQ9w6dqa
