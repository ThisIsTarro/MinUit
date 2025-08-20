# MinUIt

MinUIt (means midnight in french) is the continuiation of MinUI : a focused, custom launcher and libretro frontend for [a variety of retro handhelds](#supported-devices).
The goal for the first release is to implement QOL improvements to the frontend while keeping the original vision for simplicity, notably :
- [] Simple Menus for standalone emulators and utility paks (wrapper so anyone can use it to implement what they want and maintain design coherence)
- [] Auto-save and auto-resume for standalone emulators, with same behaviour than in minarch (savestates screenshots, resume from frontend, autosave on shutdown...)
- [] Better use of the show-version screen (Global options for brightness/volume/simple mode/wifi ?)
- [x] A Onion OS-like game switcher based on Recents list you could access from ingame (MENU + SELECT shorctut / new option in menu) and from the game list (SELECT) 
- [] A purpose for the Y button ("Add to collection" ? Sort ? Search ?)

I only own a RGB30, so I will mostly use this for testing, but I'll try my best to have platform agnostic code.
If you want to help test for other devices (listed below), [please do and report on my Discord or ping me on the RertroHandheld Discord.](https://discord.gg/MG6SNMrrBd)
<img src="github/minui-main.png" width=320 /> <img src="github/minui-menu-gbc.png" width=320 /> 

## Features

- Simple launcher, simple SD card
- No settings or configuration{({#
- No boxart, themes, or distractions
- Automatically hides hidden files
  and extension and region/version 
  cruft in display names
- Consistent in-emulator menu with
  quick access to save states, disc
  changing, and emulator options
- Automatically sleeps after 30 seconds 
  or press POWER to sleep (and wake)
- Automatically powers off while asleep
  after two minutes or hold POWER for
  one second
- Automatically resumes right where
  you left off if powered off while
  in-game, manually or while asleep
- Resume from manually created, last 
  used save state by pressing X in 
  the launcher instead of A
- Streamlined emulator frontend 
  (minarch + libretro cores)
- Single SD card compatible with
  multiple devices from different
  manufacturers


> Devices with a physical power switch
> use MENU to sleep and wake instead of
> POWER. Once asleep the device can safely
> be powered off manually with the switch.

## Supported consoles

Base:

- Game Boy
- Game Boy Color
- Game Boy Advance
- Nintendo Entertainment System
- Super Nintendo Entertainment System
- Sega Genesis
- PlayStation

Extras:

- Neo Geo Pocket (and Color)
- Pico-8
- Pokémon mini
- Sega Game Gear
- Sega Master System
- Super Game Boy
- TurboGrafx-16 (and TurboGrafx-CD)
- Virtual Boy
- **N64** // in development
- **PSP** // in development
- **NDS** // will be in first release
  
## Supported Devices

| Device | Added | Status |
| -- | -- | -- |
| Anbernic RG28xx | MinUI-20240429b-2 | Maintained |
| Anbernic RG34xx | MinUI-20241227-0 | Maintained |
| Anbernic RG35xx | MinUI-20230922b-2 | Maintained |
| Anbernic RG35xx Plus | MinUI-20240106b-0 | Maintained |
| Anbernic RG35xxH | MinUI-20240120b-1 | Maintained |
| Anbernic RG35xxSP | MinUI-20240525-0 | Maintained |
| Anbernic RG40xxH | MinUI-20240717-1 | Maintained |
| Anbernic RG40xxV | MinUI-20240831-0 | Maintained | 
| Anbernic RG CubeXX | MinUI-202401028-0 | Maintained | 
| GKD Pixel | MinUI-20240120b-1 | Maintained |
| M17 | MinUI-20231126b-2 | Maintained |
| MagicX XU Mini M | MinUI-20240831-0 | Maintained | 
| MagicX Mini Zero 28 | MinUI-20250111-0 | Maintained |
| Miyoo A30 | MinUI-20240705-0 | Maintained |
| Miyoo Flip | MinUI-20250111-0 | Maintained |
| Miyoo Mini | MinUI-20230922b-2 | Maintained |
| Miyoo Mini Plus | MinUI-20230922b-2 | Maintained |
| Powkiddy RGB30 | MinUI-20231014b-1 | Maintained |
| Trimui Brick | MinUI-20241028-0 | Maintained |
| Trimui Smart | MinUI-20230922b-2 | Maintained |
| Trimui Smart Pro | MinUI-20231111b-2 | Maintained |

> [!NOTE]
> **Active** actively working on compatibility and improvements specific to this device  
> **Maintained** inheriting improvements to common functionality  
> **Deprecated** will be retired in a future update  
> **Retired** removed from repo, no longer updated or packaged with new releases  

