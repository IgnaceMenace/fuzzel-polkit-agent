# fuzzel-polkit-agent
Simple polkit agent for window managers, using fuzzel as prompt.

## Usage
```
Usage : fuzzel-polkit-agent [-h|--help] [FUZZEL_OPTIONS]...
```

Start the polkit agent with default options :
```sh
fuzzel-polkit-agent
```

Start the polkit agent with any additional argument passed directly to fuzzel :
```sh
fuzzel-polkit-agent -theme PATH -monitor NUM
```

## Installation

### Manual Installation
- Install dependencies
- Clone this repository
- Make this script executeable (chmod +x path/to/script)
- Place script somewhere in your path

## Dependencies
| package          | source                                                |
|------------------|-------------------------------------------------------|
| sh               | a posix complient shell, preinstalled on most systems |
| coreutils        | a coreutils suit, preinstalled on most systems        |
| jq               | https://stedolan.github.io/jq/                        |
| fuzzel           | https://codeberg.org/dnkl/fuzzel                      |
| cmd-polkit-agent | https://github.com/OmarCastro/cmd-polkit              |


## Contribute
If you know anyway to make the script safer,
please leave a issue and/or make a pull request.
All help is appreciated!

## WARNING/DISCLAMIER
This script does not take any real measures to 'securely' take in the password but the use of --password flag.

## Credits
Without these programmers, this one would never had been made.
- https://github.com/OmarCastro the creator of cmd-polkit
- https://codeberg.org/dnkl     the creator of fuzzel
- https://github.com/stedolan   the creator of jq
- https://github.com/czaplicki  the creator of this script for rofi
