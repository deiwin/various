# Various scripts and snippets

## Included scripts

| Command          | Description                                                                       |
|------------------|-----------------------------------------------------------------------------------|
| `dirsize`        | Outputs the specified folder's subdirectories' sizes sorted ascendingly           |
| `type-to-window` | Types text to the specified window while preserving case                          |
| `shutdown`       | A logout/shutdown script that tries to gracefully close all apps before executing |


## Dependencies

Currently the following arch packages are used:
- [RichiH/vcsh](https://github.com/RichiH/vcsh) for dotfile management
- [xdotool](https://www.archlinux.org/packages/?name=xdotool) for the type-to-window script


## How to use

```
# Install dependencies
yaourt -S vcsh xdotool

# Clone
vcsh clone git@github.com:deiwin/various.git various

# Add $HOME/bin to your PATH
```
