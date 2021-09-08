# 🔮 Contributing to Beyond Repaired 🔮
The repo only has one branch for development and that is MasterDev.

## Table of Contents

- [Setting Up the project locally](#setting-up-the-project-locally)
- [Submitting a Pull Request](#submitting-a-pull-request)

## Setting Up the project locally

To run the project you need to use version of 3.3.5A (WOW)

1.  [Fork](https://help.github.com/articles/fork-a-repo/) the project, clone
    your fork:
    
    ```sh
    # Clone your fork
    git clone https://github.com/nizonrox/Beyond-Repair.git

    # Navigate to the newly cloned directory
    cd Beyond-Repair
    ```
2. Locate your interface folder:
    
    ```sh
    # Retail
    C:\World of Warcraft\_retail_\Interface\AddOns
    # Classic
    C:\World of Warcraft\_classic_\Interface\AddOns
    # Private Servers
    \Interface\AddOns
    ```
3. Make sure that your folder looks like this
    
    ```
    # This is inside the addons folder
    └── 📁beyond
        ├── 📁lib
        │   ├── 📄AceConsol.lua
        │   └── 📄AceConfig.lua
        ├── 📄beyond.toc
        ├── 📄beyond_lib.lua
        ├── 📑beyond_lib.xml
        ├── 🎨white16x16.tga
        └── 🎨objectIcons.tga
    ```
4. Run World of Warcraft
    After you have logged in be sure to enable the addon via the menu bottom left.
    
    <img src="https://www.almarsguides.com/Almar's%20Stuff/WoW/Addons/HowTo/Addons%20Button.jpg" alt="Addon button">

5. Recommended IDE/Documents

* [Official Lua Documentation](https://www.lua.org/pil/contents.html) // Lua is the base UI/Addon language.
* [Notepad++](https://notepad-plus-plus.org/downloads/) // Free editor /w Markdown
* [WowAce3 Lib](https://www.wowace.com/projects/ace3) // Addon lib made to make stuff easier.
* [BugGrabber](https://www.wowace.com/projects/bug-grabber) // For troubleshooting.
* [WoWLua](https://www.curseforge.com/wow/addons/wowlua) // In-game editor /w Markdown

## Submitting a Pull Request
Be sure to use a formatter for what file types you are creating/editing.<br/>
[.Xml](https://www.webtoolkitonline.com/xml-formatter.html)<br/>
[.Lua](https://goonlinetools.com/lua-beautifier/)

