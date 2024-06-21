# TSP-NewBezels

A Bezel Pack for the TrimUI Smart Pro!

![demo](https://github.com/acatone-git/TSP-NB/assets/67967964/7a5ba1ae-6588-47a7-93dc-82ff73f44c25)

# Initial Setup

- Download & extract the TSP-NB archive from the [release page](https://github.com/acatone-git/TSP-NB/releases)
- Copy to the extracted folder to X:\RetroArch\.retroarch\overlay (as example below)

![Install](https://github.com/acatone-git/TSP-NB/assets/67967964/bba418e3-60ce-4a89-ab68-1cfdaa39859d)

# Enable / Change Bezels

- Open a game from any of the supported systems & press the "Menu" button
- Select "Advanced Menu" > Scroll down & Select "On-Screen Overlay"
- Select "Overlay Preset" & Pick the config file for the system you are currently setting up
  - ex. PSX >> TSP-NB/psx_overlay.cfg
- Return to the previous menu (Press B) & Select "Overrides"
- Select "Save Content Directory Overrides" & Press the "Menu" key to exit the Advanced Menu
- Repeat the previous steps for all the desired systems

# Vertical Arcade Games Setup (Optional)

- Open a vertical arcade game & press the "Menu" button
- Select "Advanced Menu" > Scroll down & Select "Core Options"
- Select "Vertical mode" & Pick "Tate alternate"
- Return to the previous menu (Press B) & Select "Controls"
- Select "Manage Remap Files" > "Load Remap File" > "roms_best_vertical"
- Scroll down & Select "Save Game Remap File"
- Change the overlay to the vertical design (fba_vrt_overlay.cfg) following the instructions above
  - Select "Save Game Overrides" instead of "Save Content Directory Overrides"
- Press the "Menu" key to exit the Advanced Menu
- Repeat the previous steps for all your vertical games

# Enable Recommended Shaders (Optional)

- Open a game from any of the supported systems & press the "Menu" button
- Select "Advanced Menu" > Scroll down & Select "Shaders"
- Pick "Load Preset" > "shaders_glsl" & the recommended shader from the table below

| System | Recommended Shader | Alt. Shader |
|     :---:    |     :---:      |     :---:      |
| Arcade \ Home Console | crt > fake-CRT-Geom-potato | crt > crt-caligari |
| Handhelds | handhdeld > simpletex_lcd_720p | handhdeld > dot |

- Now Select "Save Preset" > "Save Core Preset"
- Press the "Menu" key to exit the Advanced Menu

# Supported Systems

| System | Bezel | Alt. Design |
|     :---:    |     :---:      |     :---:      |
| Arcade | fba_overlay.cfg / png | fba_vrt_overlay.cfg / png |
| NeoGeo Pocket | ngp_overlay.cfg / png | - |
| WonderSwan | ws_overlay.cfg / png | - |
| PC Engine | pce_overlay.cfg / png | - |
| Atari 2600 | a26_overlay.cfg / png | - |
| Atari 7800 | a78_overlay.cfg / png | - |
| Atari Lynx | linx_overlay.cfg / png | - |
| GB | gb_overlay.cfg / png | - |
| GBC | gbc_overlay.cfg / png | gbc_alt_overlay.cfg / png |
| GBA | gba_overlay.cfg / png |  gba_alt_overlay.cfg / png |
| NES / FC | fc_overlay.cfg / png | fc_alt_overlay.cfg / png |
| SNES / SFC | sfc_overlay.cfg / png | sfc_alt_overlay.cfg / png |
| N64 | n64_overlay.cfg / png | n64_alt_overlay.cfg / png |
| Game Gear | gg_overlay.cfg / png | - |
| MasterSystem | sms_overlay.cfg / png | - |
| Genesis / MegaDrive | md_overlay.cfg / png | md_alt_overlay.cfg / png (Sega CD) |
| Saturn | ss_overlay.cfg / png | - |
| Dreamcast | dc_overlay.cfg / png | - |
| Playstation | psx_overlay.cfg / png | - |
| Pico8 | p8_overlay.cfg / png | - |
| ColecoVision** | cv_overlay.cfg / png | - |

** = User Request - Core not included in the official TrimUI firmware

# Credits & Thanks

- eBay / Reddit / Launchbox DB / Wikipedia (Systems / Cartridges / Controllers Photos & Logos)
- Inkscape : https://inkscape.org/
- GIMP: https://www.gimp.org/
