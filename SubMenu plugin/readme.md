# SubMenu plugin for XEB+ Xmas Showcase

Latest version: **1.3.1 (2025-04-07)** <br>

![SubMenu plugin image](image.png)

## What is SubMenu plugin? <br>

SubMenu plugin allows you to group applications in submenus in XtremeEliteBoot+ (Xmas Showcase). <br>
You can create as many submenus as you want. <br>

## How to use SubMenu plugin? <br>

1. Extract content of **SubMenu_1.3.1.zip** (or other file if you download older version) in the XEBPLUS folder. <br>
2.  To change submenu content just edit PLG file (versions 1.3.1 and 1.3). <br>
    In older versions, submenu content can be changed in lua file in submenu folder. <br>
    Examples and instructions will be added later, but I think PLG file explains itself. <br>

## Credits:

Plugin coded by: xGamereqPL <br>

## Changelog: <br>

**SubMenu 1.3.1 - 07.04.2025**: <br>
- added support for "item without icon" (for example error message) <br>
- removed unused stuff from code <br>
- fixed graphical bug with item comments <br>

**SubMenu 1.3 - 16.03.2025**: <br>
- now submenu reads its content from PLG files, so it requires only one SubMenu.lua file <br>
- changed submenu configuration syntax <br>
- added support for comments (up to 2 lines of text in the left bottom corner), different for each submenu item <br>
- added support for .Loader, .IOPReset and .IOPDisc parameters to improve compatibility with ELF applications <br>
- added support for ContextMenu items instead of MultiELF - now context menu supports ELF and LUA applications <br>
- added support for comments (up to 5 lines of text in the bottom of the context menu), different for each context menu item <br>
- cleaned code <br>
- fixed bugs <br>

**SubMenu 1.2 - 19.05.2023**: <br>
- added checking if file exist before launching <br>
- added LuaScript support <br>
- added MultiELF support (version selection) <br>
- fixed some issues <br>

**SubMenu 1.1 - 28.03.2023**: <br>
- updated functions <br>
- new icon/description loading script (now works as it should) <br>
- code cleanup (the file is now smaller by 2 kB, unused code fragments have been removed) <br>

**SubMenu 1.0 - 25.02.2023**: <br>
- first release <br>
