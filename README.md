# Karabiner (Hotkeys)
Download [Brew](https://github.com/BosEriko/brew) as your package manager then install [Karabiner](https://formulae.brew.sh/cask/karabiner-elements).

## Install Karabiner
```sh
brew install --cask karabiner-elements
```

## Update Complex Modifications
Update your Complex Modifications with the following:
1. [Remap caps_lock to control and control+\[ to escape](capslock-overflow.json)
2. [Map left_control to ` and shift+left_control to ~](accent-and-tilde.json)
3. [Change right_command+hjkl to arrow keys](global-vim-movement.json)
4. [Swap Command and Option for all non-Apple keyboards](swap-command-option.json)
5. [Map ctrl+j/k to next/previous tab in Zen](zen-tab-navigation.json)

## Raycast
Install Raycast for quick navigation with the following:
1. Disable Spotlight: System Settings → Keyboard → Keyboard Shortcuts → Spotlight
2. Install Raycast using homebrew: `brew install --cask raycast`
3. Setup Raycast to use `right cmd` and `space bar` (if it doesn't work on setup screen, you can set it up later on settings instead)
4. Turn off Raycast AI on the settings
