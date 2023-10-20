# Goku / karabiner
This is a dump of both my setup and files, since I only do this once every 5 years.

## Goku

### Installation
`brew install yqrashawn/goku/goku`

### File locations
Goku specifically checks for `~/.config/karabiner.edn` and creates a json file at `~/.config/karabiner/karabiner.json`

### Running
- `brew services restart goku`
- `brew services restart gokuw`

### Debugging
So far this file has not been very useful/accurate to me, but atleast you can see stuff happening `~/Library/Logs/goku.log`

### Output
If all is a well a json file should be generated at the mentioned location


## Karabiner
Once you have a karabiner.json file, you can install karabiner

### Installation
Just download and install it like any other Mac application

### Preparation
Once again make sure all permissions are enabled

### Profile
If it is not created already, go to the profiles tab and create a "Default" profile

### Output
If everything went well, you should immediately be able to use the new bindings


## Basic bindings
There are some bindings I have found I cannot go without

### Option - open
These are based on the order they appear in Dock
- 1 Forklift (or Finder)
- 2 Firefox
- 3 Notes
- 4 iTerm
- 5 Phpstorm
- 6 Text Editor

### o - Open
- i iTerm
- p PhpStorm
- f Firefox
- u Firefox
- n Notes
- m Mail
- c RocketChat
- , Settings

### k - delete
There are multiple, but the most useful one:
- x Delete


