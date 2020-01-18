# SwitchSDSetup
Get AtlasNX Kosmos updates from:

https://www.sdsetup.com/console?switch#atmosphere;atmos_musthave;atmos_bootlogo;kosmos_toolkit;atmos_sigpatch;ldn_mitm;hbmenu;edizon;checkpoint;goldleaf;hekate;lockpick_rcm;

## Quick Modifications
Setting | File | Code
------------ | ------------- | -------------
Enable USB 3.0 Speed | atmosphere\system_settings.ini | usb30_force_enabled = u8!0x1
Auto Boot to CFW | bootloader\hekate_ipl.ini | autoboot=1
Reliable Backup/Restore Verification | bootloader\hekate_ipl.ini | verification=2

## Homebrew Menu
 - Hold ZR and select the Album to access
 - or Install /nsp/hbmenu.nsp and run the app