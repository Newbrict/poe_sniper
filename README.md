# PoE Sniper

A democratic PoE trade sniping tool using GNU Bash scripting.

## Requirements
A system able to run GNU Bash scripts.
* Most Linux distros
* macOS
* Windows with the [Linux Subsystem](https://msdn.microsoft.com/en-us/commandline/wsl/install_guide) installed.

## Installation
* Extract the zip to a folder.
* Launch your Bash shell.
* Install missing packages from your package manager `sudo apt-get install beep`
* `cd` into the folder `cd /mnt/c/Users/<username>/Documents/poe_sniper`
* execute command `./poe_sniper args...`

## Usage
```bash
./poe_sniper <item> <league> <(optional)max currency quantity> <(optional)currency type>
```

Example 1:
```bash
./poe_sniper 'Jewel' 'Standard'
```
Will look for any item name or type containing the string 'Jewel' in Standard at any price.

Example 2:
```bash
./poe_sniper 'Ancient Rel' 'Hardcore Standard' 5 chaos
```
Will look for any item name or type containing the string 'Ancient Rel' in the league matching 'Hardcore Standard' that is under 5 chaos orbs in price.

### Uses

* [jq](https://stedolan.github.io/jq/)
* [bc](https://www.gnu.org/software/bc/)
* [beep](https://linux.die.net/man/1/beep)

