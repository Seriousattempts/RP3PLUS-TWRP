# TWRP boot.img made for the retroid pocket 3+

These files were created from hovatek's online twrp builder https://www.hovatek.com/twrpbuilder/ along with signing them with this github repository: https://github.com/skompc/retroid-pocket-3-plus-autoroot

The twrp boot.img and vbmeta_custom.img are to replace the Boot.img and vbmeta-sign.img files in SPD ResearchDownload Tool are under releases. For RP3+ .pac file, refer to https://drive.google.com/drive/folders/1g9m8BlrCsdzXduEUfDERLilVLzxFQxX8

In SPD ResearchTool, hit the 2nd botton to the top left to access Download Settings.
*Main Page Tab*
- Change BOOT to the TWRP file.
- Change VBMETA to the vbmeta_custom file. 
*Flash Operations Tab*
- Select Erase All Flash at the bottom. (Can take 1200 secs when you start flashing to erase all).

If you ever get an NVE error, you can either go to the backup tab in Download settings and uncheck all 3 file backups at the bottom or uncheck NV_LTE under Main Page
