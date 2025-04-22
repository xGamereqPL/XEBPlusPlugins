# ContextMenu plugin for XEB+ Xmas Showcase

Latest version: **1.3 (2025-03-16)** <br>

![ContextMenu plugin image](image.png)

## What is ContextMenu plugin? <br>

ContextMenu plugin allows you to group applications in context menus in XtremeEliteBoot+ (Xmas Showcase). <br>
You can create as many context menus as you want. <br>

## How to use ContextMenu plugin? <br>

1. Extract content of **ContextMenu_1.3.zip** (or other file if you download older version) in the XEBPLUS folder. <br>
2.  To change context menu content just edit PLG file (versions 1.3). <br>
    In older versions, context menu content can be changed in lua file in context menu folder. <br>
    Examples and instructions will be added later, but I think PLG file explains itself. <br>

## Credits:

Plugin coded by: xGamereqPL <br>

## Changelog: <br>

**ContextMenu 1.3 - 16.03.2025**: <br>
- now context menu reads its content from PLG files, so it requires only one ContextMenu.lua file <br>
- changed context menu configuration syntax <br>
- added support for .Loader, .IOPReset and .IOPDisc parameters to improve compatibility with ELF applications <br>
- added support for LUA items, now context menu can have both ELF and LUA applications
- added support for comments (up to 5 lines of text in the bottom of the context menu), different for each context menu item <br>
- cleaned code <br>
- fixed bugs <br>

**ContextMenu 23-04-2023 - 23.04.2023**: <br>
- first release <br>
