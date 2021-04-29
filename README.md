# ECM Timer

## Overview

Key features and options:

- **ECM Timer:** Adds a timer to the HUD when an ECM or Pocket ECM is active. If multiple ECMs are active, the longest duration is used. No distinction is made between basic and pager-blocking ECMs.

## Known Issues

When an ECM is despawned (and thus is no longer active), the ECM timer still continues counting down. Due to the low likelihood of this occurring during typical gameplay and the fact that this issue isn't game-breaking, there are no plans to change it at this time.

When joining a game while an ECM is already active, the ECM timer will not be shown (but any new ECMs placed after joining will work fine). This cannot be fixed because the game does not sync the remaining ECM time to clients who drop in.

## Installation

This mod requires [SuperBLT](https://superblt.znix.xyz).

Download `ECM-Timer_<ver>.zip` from the [latest release page](https://github.com/ncakes/PD2-ECM-Timer/releases/latest) and extract the entire contents to your `mods` folder.

```
C:\Program Files (x86)\Steam\steamapps\common\PAYDAY 2\mods
```

## Acknowledgments

This mod has been adapted from LazyOzzy's ECM duration timer which can be found [here](https://www.unknowncheats.me/forum/payday-2-a/122868-ecm-duration-timer.html).
