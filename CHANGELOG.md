# Change Log

All notable changes to the "discord-py-snippets" extension will be documented in this file.

## [1.0.0]

- Initial release of discord.py-snippets extension

## [1.0.1]

- Fixed some bugs

## [1.1.0]

- Added 3 new snippets, `!gbchk`, `cgchk` & `!embedhelp`
- Added more info in the readme file

## [1.2.0]

- Added not shadowing command snippets (for function names for commands that are already defined eg. eval)
- Added embed snippets
  - embed
  - field
  - footer
  - author
  - image
  - thumbnail

### [1.2.1]

- Fixed a issue in the `!emb` snippet where there were double commas

### [1.2.2]

- Fixed a issue in the `!emb` snippet where there was a : where there shouldn't be one

### [1.3.0]

- Added Group Template `!grp`
- Added Group command Template `!grpcmd`
- Made event names always start with `on_`
- Made it easier to add commands with aliases
- Changed the command in `!dpstrt` from `test` to `hello`
- Made it easier to know what a value is for

### [1.3.1]

- Fixed a bug in `!cgcmd` where the aliases field would have a unnecessary comma

### [1.4.0]

- Changed the `!cog` snippet to use the current file name as the cog name, thanks to QuaKe
- Added `!owner_only` check
- Added `!nsfw_only` check
- Added `!hasperms` check
- Added `!cooldown` decorator
- Added `!waitforreaction` snippet
- Added `!waitformessage` snippet


### [1.4.1]

- Added UI Category with `!button`, `!cbutton` and `!select`
- Added `!excpt` snippet
- Fixed indendation in `!embedhelp`
