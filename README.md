# [Arcade: Mario Bros](https://www.arcade-museum.com/game_detail.php?game_id=8624) for [MiSTer](https://github.com/MiSTer-devel/Main_MiSTer/wiki)

Arcade: Mario Bros port to MiSTer by [gaz68](https://github.com/gaz68) - June 2020  
Original Donkey Kong port to MiSTer by [Sorgelig](https://github.com/sorgelig) - 18 April 2018

#### Sources

[dkong](https://web.archive.org/web/20190330043320/http://www.geocities.jp/kwhr0/hard/fz80.html)  Copyright (c) 2003 - 2004 by Katsumi Degawa  
[T80](https://opencores.org/projects/t80)   Copyright (c) 2001-2002 Daniel Wallner (jesus@opencores.org) All rights reserved  
[T48](https://opencores.org/projects/t48)   Copyright (c) 2004, Arnim Laeuger (arniml@opencores.org) All rights reserved  

## Description

This is an FPGA-based recreation of the Mario Bros Arcade system from 1983 for the MiSTer FPGA open source platform.

### Controls

Keyboard Inputs:

| Key          | Description     |
| ------------ | --------------- |
| F2           | Start 2 players |
| F1           | Start 1 player  |
| SPACE        | Jump            |
| LEFT,RIGHT   | Move left/right |

MAME/IPAC/JPAC Style Keyboard inputs:
| Key          | Description        |
| ------------ | ------------------ |
| 5            | Coin 1             |
| 6            | Coin 2             |
| 1            | Start 1 Player     |
| 2            | Start 2 Players    |
| D,G          | Player 2 Movements |
| A            | Player 2 Jump      |

Joystick support.

### ROM Files Instructions

**ROMs are not included!** In order to use this arcade core, you will need to provide the correct ROM file yourself.

To simplify the process `.mra` files are provided in the releases folder, that specify the required ROMs with their checksums. The ROMs `.zip` filename refers to the corresponding file from the MAME project.

Please refer to https://github.com/MiSTer-devel/Main_MiSTer/wiki/Arcade-Roms for information on how to setup and use the environment.

Quick reference for folders and file placement:

```
/_Arcade/<game name>.mra
/_Arcade/cores/<game rbf>.rbf
/games/mame/<mame rom>.zip
/games/hbmame/<hbmame rom>.zip
```
