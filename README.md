# SwitchSDSetup
Get AtlasNX Kosmos updates from:

https://sdsetup.com/console?switch#atmosphere;atmos_musthave;atmos_bootlogo;kosmos_toolkit;atmos_sysftpd;atmos-sys-con;ldn_mitm;hbmenu;checkpoint;edizon;goldleaf;hekate;lockpick_rcm;atmos_sigpatch;

## Quick Modifications
Setting | File | Code
------------ | ------------- | -------------
Auto Boot to CFW | bootloader\hekate_ipl.ini | ```autoboot=1```
Reliable Backup/Restore Verification | bootloader\hekate_ipl.ini | ```verification=2```
FTP Login Details | config\sys-ftpd\config.ini | ```user:=``` and ```password:=```

## Homebrew Menu
 - Hold ZR and select the Album to access
 - or Install /nsp/hbmenu.nsp and run the app

 ## Submodules
 To enable/disable submodules:
 - Open the Homebrew menu (see above)
 - Run the "Kosmos Toolbox" app
 - Select "Background services"

 The following are avaialble:
 Name | Description |
 ------------ | -------------
sys-ftpd-light | FTP server (see config location above)
ldn_mitm | Play local wireless games online ([More Info](https://gbatemp.net/threads/ldn_mitm-play-local-wireless-supported-games-online.525512/))
sys-con | Support controllers via USB: Xbox 360, Xbox One, PS3 & PS4
