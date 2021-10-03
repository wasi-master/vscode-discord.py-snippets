# What is discord-py-snippets

A simple snippets extension for the [discord.py](https://discordpy.readthedocs.io/en/latest/ "discord.py Documentation") package for [python](https://www.python.org "python.org")

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=WasiMaster.discord-py-snippets">
    <img alt="VS Code Marketplace Downloads" src="https://img.shields.io/visual-studio-marketplace/d/WasiMaster.discord-py-snippets">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=WasiMaster.discord-py-snippets">
    <img alt="VS Code Marketplace Installs" src="https://img.shields.io/visual-studio-marketplace/i/WasiMaster.discord-py-snippets">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=WasiMaster.discord-py-snippets#review-details">
    <img alt="VS Code Marketplace Rating" src="https://img.shields.io/visual-studio-marketplace/r/WasiMaster.discord-py-snippets">
  </a>

</p>

## Features

### Making a cog

![Cog Example](https://i.imgur.com/gIWNM5E.gif)

### Making a command

![Command Example](https://i.imgur.com/jUQZywQ.gif)

### Starter Template

![Starter Example](https://i.imgur.com/waHtA9I.gif)

### Making a event

![Event Example](https://i.imgur.com/AcoHPfb.gif)

### Using the library aiohttp to use a api in a command

![AioHTTP Example](https://i.imgur.com/LVZVq33.gif)

<!-- ## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something -->

## All Snippets

### Normal Snippets

| Name                                        | Prefix       | Description                                                                                                         |
|---------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------|
| Starter Template                            |   `!dpstrt`  | A starter template                                                                                                  |
| Basic Command Template                      |    `!cmd`    | A basic command template (Not for cogs)                                                                             |
| Basic Event Template                        |    `!evt`    | A basic event template (Not for cogs)                                                                               |
| Cog Command Template                        |   `!cgcmd`   | A basic command template for cogs                                                                                   |
| Cog Event Template                          |   `!cgevt`   | A basic event template for cogs                                                                                     |
| Cog Template                                |    `!cog`    | A starter template for a cog                                                                                        |
| aiohttp Template                            |    `!ahtp`   | A basic aiohttp web request template (You need to have bot.session defined as a instance of aiohttp.ClientSession)  |
| Global Check Template                       |    `gbchk`   | A basic global check template                                                                                       |
| Cog Check Template                          |   `!cgchk`   | A basic cog check template                                                                                          |
| Embed Help                                  | `!embedhelp` | A custom help command implementation that modifies the default help and uses embed                                  |
| Not Shadowing Command Template              |  `!unscmd`   | A basic command template that doesn't shadow another function (Not for cogs)                                        |
| Cog Not Shadowing Command Template          |  `!cgunscmd` | A basic command template that doesn't shadow another function for cogs                                              |
| Group Template                              |    `!grp`    | A group template (Can be used in cogs)                                                                              |
| Group Command Template                      |   `!grpcmd`  | A basic group command template (Can be used in cogs)                                                                |
| Wait for reaction Template                  | `!waitforreaction` | A wait for template for on_reaction_add
| Wait for message Template                   | `!waitformessage` | A wait for template for on_message
| Discord based exception                     | `!except`    | A basic exception template based on a discord error

### Embed Snippets

| Name                                        | Prefix       | Description                  |
|---------------------------------------------|--------------|------------------------------|
| Embed Template                              |   `!emb`     | Makes a Embed                |
| Embed Field Template                        | `!embfield`  | Adds a field to a embed      |
| Embed Footer Template                       |  `!embfoot`  | Adds a footer to a embed     |
| Embed Author Template                       | `!embauthor` | Adds a author to a embed     |
| Embed Thumbnail Template                    |  `!embthumb` | Adds a image to a embed      |
| Embed Image Template                        |  `!embimg`   | Adds a thumbnail to a embed  |

### Check Snippets

| Name                                        | Prefix       | Description                           |
|---------------------------------------------|--------------|---------------------------------------|
| Owner only check Template                   | `!owneronly` | Sets a command as owner_only          |
| NSFW only check Template                    | `!nsfwonly`  | Sets a command as nsfw only           |
| Has Permissions check Template              | `!hasperms`  | makes a command require a permission  |

### UI

| Name                                        | Prefix       | Description                           |
|---------------------------------------------|--------------|---------------------------------------|
| Button                                      |  `!button`   | A basic button                        |
| Custom Button                               |  `!cbutton`  | A button with a custom constructor    |
| Select                                      |  `!select`   | A basic select                        |

## Tips and Tricks

- Use Tab to navigate between required inputs
- Use Shift+Tab to edit the previous input
- Once a input is focused on, press backspace and then press tab to skip it if you don't want to add that
- Once a input is focused on, press tab to skip and keep the default value
- If you don't want something, you can press backspace to remove it

## Known Issues

There isn't many snippets so any suggestions for snippets would be appreciated

## Contribute

You can open a pull request anytime and I will look into it\
I suggest seeing the [vscode snippets documentation](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_create-your-own-snippets "VSCode Snippets Documentation") before you open a pull request

## Release Notes

### 1.0.0

- Initial release of discord.py-snippets

### 1.0.1

- Fixed some bugs

### 1.1.0

- Added 3 new snippets, `!gbchk`, `cgchk` & `!embedhelp`\
- Added more info in the readme file

### 1.2.0

- Added not shadowing command snippets (for function names for commands that are already defined)
- Added embed snippets
  - embed
  - field
  - footer
  - author
  - image
  - thumbnail

### 1.2.1

- Fixed a issue in the `!emb` snippet where there were double commas

### 1.2.2

- Fixed a issue in the `!emb` snippet where there was a : where there shouldn't be one

### 1.3.0

- Added Group Template `!grp`
- Added Group command Template `!grpcmd`
- Made event names always start with `on_`
- Made it easier to add commands with aliases
- Changed the command in `!dpstrt` from `test` to `hello`
- Made it easier to know what a value is for

### 1.3.1

- Fixed a bug in `!cgcmd` where the aliases field would have a unnecessary comma

### 1.4.0

- Changed the `!cog` snippet to use the current file name as the cog name, thanks to QuaKe
- Added `!owner_only` check
- Added `!nsfw_only` check
- Added `!hasperms` check
- Added `!cooldown` decorator
- Added `!waitforreaction` snippet
- Added `!waitformessage` snippet

### 1.5.0

- Added UI Category with `!button`, `!cbutton` and `!select`
- Added `!except` snippet
- Fixed indendation in `!embedhelp`

### Extensions in the screenshots

- [Monokai Pro](https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode) by [monokai](https://marketplace.visualstudio.com/publishers/monokai)

- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) by [CoenraadS](https://marketplace.visualstudio.com/publishers/CoenraadS)

- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) by [Street Side Software](https://marketplace.visualstudio.com/publishers/streetsidesoftware)

- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) by [Microsoft](https://marketplace.visualstudio.com/publishers/Microsoft)

-----------------------------------------------------------------------------------------------------------


**Enjoy!**
