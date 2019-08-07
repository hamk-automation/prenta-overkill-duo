# Prenta Duo Valkeakoski
## Marlin 3D Printer Firmware, 2.0 bugfix 

Additional documentation can be found at the [Marlin Home Page](http://marlinfw.org/).

This is repo for maintaining HAMK Valkeakoski's Prenta Duo machine, upgraded with SKR 1.3 32bit board, TMC5160 drivers, BLTouch, e3d nozzle X and other minor quality of life upgrades. By default the printer operates in TMC stealthchop mode and stallguard for XY homing. Nozzle setup is 0.6mm/nozzle1 and 0.4mm/nozzle 2. Nozzle 2 is not usable as of September 2019. 

** _"Dual extruder setups create more problems than they solve"_ - © Erkki Honkakoski **

The printer now have following features: 
1. Automatic bed leveling (bilinear, 9 points)
2. dead silent operation and freaking smart drivers
3. it prints. 

The slicing configs are in the PrusaSlicer folder, merge it manually in your %appdata% (windows = c:/users/your_main_username/AppData/Roaming/PrusaSlicer). Do this at your own risk and check each overwrite carefully so you don't screw up your existing configs in PrusaSlicer (if any). In the future when Prusa fix their "export config bundle" feature this will be more simple. Slicing profile includes a mario flagpole tone at the end, remove the m303 segments from slicer printer settings if you feel annoyed. 

Feel free to experiment with marlin 2.0 main branch, make pull request if you think there is feature that should be deployed/added or my tunings are not good enough per your standard. 

© kdang 2019