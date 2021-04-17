# Snapmaker 2.0 - Prusa Slicer Profiles

This repo contains prusa slicer profiles specifically made to be used by Snapmaker 2.0 3D printers.

Since I own an A250 myself, expect that to be the main focus. Should you own a 150 or 350, feel free to
adapt them to work on your machine. I will not make them since I cannot verify them.

Also, I have the SM2.0 enclosure as well which might impact your prints if you don't. Have not tested to
see if that makes a big difference. Feel free to let me know.

# Profiles

If you add additional profiles, please add them to this section

## Complete bundles (printer/filament/print settings combined)
### A250-PETG

PETG support, not the fastest profile, but produces reliable prints.

Be careful though, the PETG will stick hard to your bed if you leave it there to cool off!

## Printers
### A350
Contains 
 - model (credits to the late [@stefix](https://forum.snapmaker.com/u/stefix))
 - print sheet texture (SVG)
 - printer settings

Note that you will have to set the model/texture in the `Bed shape` setting, unless you happen to be on Windows and saving the model/sheet to the same place

## Print Settings
### MatterHackers Build PETG
Mostly the same from the A250-PETG setup, tweaked infill and temperature.

## Filament Settings
### MatterHackers Build PETG
 - Transluscent Green
 - White

Not much configured in here other than colors (mostly the same as the A250-PETG bundle).

# Credit

Initial A250 PETG profile is based on the A350 PLA work by Edwin LIU from the snapmaker forums
- https://drive.google.com/drive/folders/1xfBgXZzwjKaeZ3iqscdpe2xosgFV03G0
- https://forum.snapmaker.com/t/prusa-slicer-profile/5657/4
