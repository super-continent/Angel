# Angel
An improvement mod for Arcana Heart 3 LOVEMAX SIXSTARS!!!!!! XTEND

## Installation
Download from [the releases page](https://github.com/super-continent/Angel/releases/latest) and place `dinput8.dll` into your `ArcanaHeart3LMSS/` install folder.

In order to prevent rare crashes when loading into a match, it's recommended to apply a Large Address Awareness patch to AALib.exe, such as [4GB Patch](https://ntcore.com/4gb-patch/).

## Features
### Better Online Play
- Player Match lobbies and Ranked Match now use rollback versus modded players
- Delay-based netcode is used as a fallback versus unmodded opponents
- Unmodded players can spectate modded rollback matches
- "Save replay?" prompt now has a 10-second timer which automatically selects "No" and returns to lobby, so modded players can never accidentally stall lobbies by going AFK
- Entering Network mode is now faster, with initialization being 3 seconds faster, and the Steam cloud sync popup notice no longer displaying upon entry
### More Display Menu Options
- Borderless fullscreen mode
- Windowed resolutions now go past 1080p
### Custom Palettes
- Palette editor which allows overriding character/arcana palettes with custom colors
- Custom palettes sync between players in online lobbies (opt-in)
### Improved Replays
- Replays are now stored in a custom format, which uses over 99% less storage on average
- Replays are automatically converted to the new format upon launch, with a backup folder containing the original files
- The limit of 99 replays has been removed
- Saved replay files now have more descriptive names
### Extra Training Mode Tools
- Hitbox display
- Pause and frame advance hotkeys
- Save/Load state hotkeys
- Hide battle HUD option

## Credits
Thanks to [Armonté](https://github.com/Armonte) for doing much of the reverse-engineering work that was needed to implement rollback

Thanks to XeNO for providing info used to create the hitbox viewer
