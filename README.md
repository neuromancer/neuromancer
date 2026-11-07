I'm part of the [ScummVM](https://www.scummvm.org/) team, volunteering as the main developer for the reimplementation of the following engines/games:

**Private**: point and click engine by [Brooklyn Multimedia](https://www.mobygames.com/company/2861/brooklyn-multimedia/) for [Private Eye (1996)](https://www.mobygames.com/game/7117/private-eye/) 

<img src="https://www.scummvm.org/data/screenshots/private/private-eye/private-eye_win_en_1_1_full.png" width="350" alt="private eye">

**Hypno**: engine by Hypnotix for point and click and rail shooters including [Wetlands (1995)](https://www.mobygames.com/game/862/wetlands/), [Marvel Comics Spider-Man: The Sinister Six (1996)](https://www.mobygames.com/game/34907/marvel-comics-spider-man-the-sinister-six/) and [Soldier Boyz (1997)](https://www.mobygames.com/game/8383).

<img src="https://www.scummvm.org/data/screenshots/hypno/wetlands/wetlands_dos_en_1_2_full.png" width="350" alt="wetlands">

**Freescape**: one of the first 3D engines, developed by Incentive Software for a number of games:
* [Driller/Space Station Oblivion (1987)](https://www.mobygames.com/game/4933)
* [Dark Side (1988)](https://www.mobygames.com/game/21802)
* [Total Eclipse (1988)](https://www.mobygames.com/game/6712) / [Total Eclipse 2 (1989)](https://www.mobygames.com/game/71411)
* [Castle Master (1990)](https://www.mobygames.com/game/2155) / [Castle Master 2 (1990)](https://www.mobygames.com/game/2169)
* [3D Construction Kit / Virtual Reality Kit (1991)](https://www.mobygames.com/game/391)

<img src="https://www.scummvm.org/data/screenshots/freescape/castlemaster/castlemaster_dos_en_1_1_full.png" width="350" alt="castle master">

**Colony**: one of the first engines with real-time 3D graphics and free movement, created by David Alan Smith for [The Colony (1988)](https://www.mobygames.com/game/3489)

<img src="https://www.scummvm.org/data/screenshots/colony/colony/colony_mac_en_2_2_full.png" width="350" alt="colony">

**EEM engine**: point and click detective engine by Stormfront Studios for [Eagle Eye Mysteries (1993)](https://www.mobygames.com/game/14171) and [Eagle Eye Mysteries in London (1994)](https://www.mobygames.com/game/19256)

<img src="https://www.scummvm.org/data/screenshots/eem/eem/eem_dos_en_1_2_full.png" width="350" alt="eagle eye">

**SCUMM**: reimplementation of the FMV rail shooters by LucasArts, including [Star Wars: Rebel Assault (1993)](https://www.mobygames.com/game/272), [Star Wars: Rebel Assault II - The Hidden Empire (1995)](https://www.mobygames.com/game/5800) and [Mortimer and the Riddles of the Medallion (1996)](https://www.mobygames.com/game/9778)

<img src="https://www.scummvm.org/data/screenshots/scumm/rebel2/rebel2_dos_en_1_2_full.png" width="350" alt="rebel assault ii">

## Source code reconstruction

Outside of ScummVM, I completed a full [source code reconstruction](https://github.com/neuromancer/my-teacher-is-an-alien-re) of [Bruce Coville's My Teacher Is an Alien (1997)](https://www.mobygames.com/game/157029/bruce-covilles-my-teacher-is-an-alien/), a point and click adventure by [7th Level](https://www.mobygames.com/company/793/7th-level-inc/). The code is bug-for-bug faithful: built with the original tools, it matches the retail binary at the CPU instruction level, verified with [binary-comp](https://github.com/neuromancer/binary-comp), a tool I created to compare binaries function by function.

<img src="https://github.com/user-attachments/assets/a0ac2b7e-36ea-4e8a-b6ad-d5e4988e2a83" width="350" alt="my teacher">

I have also used AI agents to automatically reconstruct the source code of the first two [Wing Commander](https://www.mobygames.com/game-group/wing-commander-series) games as shipped in *The Kilrathi Saga* (1996). Both **fully 100% matching the original executables** Win32 executables with the period Microsoft Visual C++ toolchain, and both ship a native SDL2 port for Windows, Linux and macOS running on Kilrathi Saga or DOS game data:

* [wc1-re](https://github.com/neuromancer/wc1-re): Wing Commander (1990)
* [wc2-re](https://github.com/neuromancer/wc2-re): Wing Commander II (1991)
 
<img src="https://raw.githubusercontent.com/neuromancer/wc1-re/main/screenshots/cockpit-combat.png" width="350" alt="wing commander"> <img src="https://raw.githubusercontent.com/neuromancer/wc2-re/main/screenshots/cockpit-navigation.png" width="350" alt="wing commander ii">

## mystery-o-matic

I'm a detective-story geek who created [mystery-o-matic.com](https://mystery-o-matic.com), a website where you can solve a daily murder mystery in 5 minutes. All [the code and website](https://github.com/mystery-o-matic/mystery-o-matic.github.io/) are open-source!
