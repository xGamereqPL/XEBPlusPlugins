# XETTINGS plugin for XEB+ Xmas Showcase

Latest version: **1.3.1 (2025-03-30)** <br>

![XETTINGS plugin image](image.png)

## What is XETTINGS? <br>

XETTINGS is a plugin for XtremeEliteBoot+ (Xmas Showcase). <br>
Allows you to change XEB+ settings directly from the dashboard. <br>
This feature has been removed from the Xmas Showcase, but you can bring it back with this plugin. <br>
You also can change XtremeBootloader settings (USB Drivers) that cannot be changed in xebplus.cfg. <br>
This plugin also adds some custom features, like more date formats. <br>

## How to install XETTINGS? <br>

Extract content of **XETTINGS_1.3.1.zip** (or other file if you download older version) in the XEBPLUS folder. <br>

## Warnings:

Use this plugin only with XEB+ Xmas Showcase. <br>
Do not use this plugin if you run XEB+ from host:/ (PCSX2), it will corrupt the CFG file (but it seems to work with the latest nightly PCSX2 version). <br>
Exit to Browser only works on some console models (I can confirm it works on SCPH-50004 - ROMVER 1.70) <br>
After changing the USB Drivers, the options saves to mc?:/BOOT/XBL.CNF or mc?:/SYS-CONF/XBL.CNF (only if the BOOT or SYS-CONF folder exists). In case of problems after changing the drivers, delete this file. <br>

## Credits:

Plugin coded by: xGamereqPL <br>
Spanish translations: Howling Wolf & Chelsea, P4NCHOL1NO <br>
Portuguese translations: MayconTp, nuno6573 <br>

## Changelog: <br>

**XETTINGS 1.3.1 - 30.03.2025**: <br>
- cleaned submenu code <br>
- fixed bug: when theme previews were disabled, they were still displayed in "theme settings" submenu <br>
- fixed bugs with saving XBL.CNF file <br>

**XETTINGS 1.3 - 16.03.2025**: <br>
- updated ContextMenu and SubMenu <br>
- updated translations <br>
- theme: new theme selection menu with smoother previews and improved sorting script <br>
- theme: added "Loading themes list..." and "Loading theme preview..." texts <br>
- video mode: fixed issues in "confirm video mode" screen <br>
- date format: added new date formats (MM-DD-YYYY, DD-MM-YYYY, MM.DD.YYYY, DD.MM.YYYY) <br>
- USB drivers: moved warning text to the left (like in Default IOP reset method) <br>
- USB drivers: added new XBL.CNF path - mc?:/BOOT/XBL.CNF <br>
- added XETTINGS configuration submenu <br>
- XETTINGS configuration: added Loading themes list progress <br>
- XETTINGS configuration: added Theme preview settings <br>
- XETTINGS configuration: added Configure "Exit to browser" <br>
- added function to display theme selection menu in submenu, useful in "theme settings" submenus <br>
- changed some texts <br>
- cleaned code <br>
- fixed bugs <br>

**XETTINGS 1.2 - 22.05.2023**: <br>
- context menu coded from scratch (now uses fontSmall) <br>
- theme preview fades out smoother <br>
- added exit code to the childproof mode context menu <br>
- changed context menu texts position <br>
- bug fixes <br> <br>

**XETTINGS 1.1 - 22.04.2023**: <br>
- updated "Refresh" option. <br>
- renamed "Exit to Browser" to "Restart" to better describe what it does <br>
- moved "Disc launch behavior", "Date format", "Type of clock" and "Default IOP reset method" settings to "XEB+ Configuration" submenu <br>
- added real "Exit to Browser" [EXPERIMENTAL] <br>
- added "USB Drivers" (to the submenu) [EXPERIMENTAL] <br>
- added themes list scrolling <br>
- moved theme info to the left screen side (under the preview) <br>
- added video mode change confirmation <br>
- moved xebplus.cfg saving function to PLG_XETTINGS.lua <br>
- fixed some issues <br> <br>

**XETTINGS 1.0 - 22.03.2023**: <br>
- first release <br>
