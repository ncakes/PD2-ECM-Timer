# ECM Timer

## Overview

Key features and options:

- **ECM Timer:** Adds a timer to the HUD when an ECM or Pocket ECM is active. If multiple ECMs are active, the longest duration is used. No distinction is made between basic and pager-blocking ECMs.

## Known Issues

- When an ECM is despawned (and thus is no longer active), the ECM timer still continues counting down normally.
- When the police assault banner is active, the hostage panel is moved down and obscures the ECM timer.

Due to the low likelihood of these occurrences during typical gameplay and the fact that these issues are not game-breaking, there are no plans to fix them at this time.

## Installation

This mod requires [SuperBLT](https://superblt.znix.xyz).

Download `ECM-Timer_<ver>.zip` from the [latest release page](https://github.com/ncakes/PD2-ECM-Timer/releases/latest) and extract the entire contents to your `mods` folder.

```
C:\Program Files (x86)\Steam\steamapps\common\PAYDAY 2\mods
```

## Acknowledgments

This mod is based on LazyOzzy's ECM duration timer which can be found here [here](https://www.unknowncheats.me/forum/payday-2-a/122868-ecm-duration-timer.html).

The code used for calculating the remaining ECM time was written by me.

The code used for displaying the time on the HUD was written by LazyOzzy (`hudmanagerpd2.lua`). I have made a few adjustments to the icon and counter.
