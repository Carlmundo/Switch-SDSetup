# SwitchSDSetup
Get AtlasNX Kosmos updates from:
https://www.sdsetup.com/console?switch#atmosphere;atmos_musthave;atmos_bootlogo;kosmos_toolkit;atmos_sigpatch;hbmenu;edizon;checkpoint;tinfoil;goldleaf;lockpick;retroarch;retroarch_snes9x2010;retroarch_pcsxra;retroarch_gengxp;hekate;

## Quick Modifications
Setting | File | Code
------------ | -------------
Enable USB 3.0 Speed | atmosphere\system_settings.ini | usb30_force_enabled = u8!0x1
Auto Boot to CFW | bootloader\hekate_ipl.ini | autoboot=1
Reliable Backup/Restore Verification | bootloader\hekate_ipl.ini | verification=2

