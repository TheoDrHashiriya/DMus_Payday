# Doom Dynamic Music: PAYDAY
- A music pack that adds dynamic tracks from the Payday series to Doom. The control phases of each song are played whenever the player is not in combat and then transitions to the assault phases when in combat.
- The control and assault phases are seamlessly looped with the help of ZDoom's audio looping feature and Audacity.
- The original Doom tracks are manually muted using a blank music file to prevent them from playing briefly during level loading.
- Due to the state of the mod, the anticipation phases of each track cannot be implemented like in the Payday games unfortunately.
- Please do report any inconsistencies and issues with the audio looping and volume. I'm terribly nitpicky about those.
- Suggestions, especially for specific Payday tracks, are welcome in the issues page.

## Pros & Cons
### Pros
- Boosts morale.
- Increases operation speed.

### Cons
- Increases mortality rate.
- Non-ideal for long operations; Novelty fades.
- [Known Issues](https://github.com/TheoDrHashiriya/DMus_Payday#known-issues--their-solutions).

## Installation
A. Repository (Latest)
1. Download the DoomDynMus mod [here](https://github.com/cyberc001/DoomDynMus/archive/refs/heads/master.zip).
2. Download the music pack repo [here](https://github.com/TheoDrHashiriya/DMus_Payday/archive/refs/heads/main.zip).
3. Open the music pack archive.
4. Open the *DMus_Payday-main* folder.
5. Select all the contents inside the folder and copy them.
6. Paste the contents directly outside of that folder.
7. Delete *DMus_Payday-main*.
8. Load both the new music pack archive and the mod into GZDoom.

B. Release
1. Download the DoomDynMus mod [here](https://github.com/cyberc001/DoomDynMus/archive/refs/heads/master.zip).
2. Download the music pack release [here](https://github.com/TheoDrHashiriya/DMus_Payday/releases/download/v1.0/DMus_Payday-v1.0.pk3).
3. Load both the music pack archive and the mod into GZDoom.

### Load Order
- Load DMus_Payday, and any other music packs, before DoomDynMus.
- Load the music pack and the mod before any mods that alter enemy AI.

### Usage
- See the mod page's [Features list](https://forum.zdoom.org/viewtopic.php?f=43&t=72207#p1188860).

## Known Issues (& Their Solutions)
- The game freezes on level start when loading the cloned repo and the mod without extracting and repacking the music pack first. See this [issue page](https://github.com/cyberc001/DoomDynMus/issues/2).
- The game will crash with a VM execution aborted error in some instances. Although it was fixed by cyberc001, it still persists at times.\
The current available workaround is to press the Escape button and start a new game. For more info, here's the [issue page](https://github.com/cyberc001/DoomDynMus/issues/1).
- Using mods that modify enemy AI causes complications, like the switching back and forth between the control and assault phases when using [Ugly as Sin](https://github.com/caligari87/Ugly-as-Sin/)'s Advanced AI module. Load the music pack and the mod before any mods that alter enemy AI. If issue persists, remove the AI mod from the load order.
- ~~Due to how text files are cloned, there will be an extra blank line in the DMUSDESC file when downloaded to .zip. Meaning, it will register a silent track group that causes a crash. Delete this extra line from the DMUSDESC file.~~

## Audio Info
### Audio Source:
- CommanderCH's PAYDAY 2 [Stealth](https://www.dropbox.com/s/ibtl9dt7jw2m1x7/PD2%20Sountracks%20Stealth.zip?dl=0), [Control](https://www.dropbox.com/s/7q0h4k0oxg15p4g/PD2%20Soundtracks%20Control.zip?dl=0), [Assault](https://www.dropbox.com/s/49j5dm3z1icb4hr/PD2%20Soundtracks%20Assault.zip?dl=0) Phases Soundtracks
- Uploaded tracks on YouTube.

### Audio Quality:
- Source: 160 kb/s MP3, 128-152 kb/s OGG Opus
- Mod   : Quality level 5 OGG Vorbis (Converted the music files to OGG Vorbis because MP3 and OPUS does not support audio looping.)

### Tracklist (DMUSDESC Order):
1. Le Castle Vania - Use of Force
2. Le Castle Vania - Infinite Ammo
3. Le Castle Vania - Fully Loaded Epic Win
4. Simon Viklund - Gun Metal Grey
5. Simon Viklund - Razormind
6. Simon Viklund - The Mark
7. Simon Viklund - Code Silver
8. Simon Viklund - Tick Tock
9. Simon Viklund - The Gauntlet
10. Simon Viklund - Wanted Dead or Alive
11. Simon Viklund - Calling all Units
12. Simon Viklund - Backstab
- Simon Viklund - Criminal Intent (Main Menu Theme)
- Simon Viklund - See You at the Safe House (Intermission Theme)
- Simon Viklund - Busted (Death Theme)

## Credits
### Mod
cyberc001\
\
[cyberc001's DoomDynMus ZDoom Page](https://forum.zdoom.org/viewtopic.php?f=43&t=72207)\
[cyberc001's DoomDynMus GitHub repo](https://github.com/cyberc001/DoomDynMus)\
[ZDoom Wiki: Audio Loop](https://zdoom.org/wiki/Audio_loop)\
[Music looping guide using tags](https://forum.zdoom.org/viewtopic.php?f=39&t=48364)\
[Audacity](https://www.audacityteam.org/)

### Music
Simon Viklund\
Le Castle Vania\
CommanderCH\
\
[Simon Viklund's official website](http://www.simonviklund.com)\
[Le Castle Vania's official website](https://lecastlevania.com/)\
[PAYDAY - The Game Soundtrack](https://overkillsoundtracks.bandcamp.com/album/payday-the-game-soundtrack)\
[PAYDAY 2 Official Soundtrack](https://overkillsoundtracks.bandcamp.com/album/payday-2-official-soundtrack)\
[CommanderCH's PAYDAY 2 Phases Playlists](https://www.youtube.com/c/CommanderCH/playlists?view=50&sort=dd&shelf_id=16)
