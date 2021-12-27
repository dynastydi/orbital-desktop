Custom configuration for AwesomeWM, scripted in Lua and shell.
A beautiful, minimalist, productivity-focused setup inspired by the _Culture_ sci-fi novels.

![Screenshot_20211226_182735](https://user-images.githubusercontent.com/86522370/147416986-e86587ab-eccf-4538-b91a-4fd249c60629.png)


Includes subtle diagnostics via shell scripting, including: network status, CPU temps, disk capacities & availabilities and battery charge (if appropriate). These scripts run simple Linux bash commands - they may not translate on every system, and can be commented out or adjusted if buggy.

Install is as simple as running:

```
${favourite_package_manager} awesome dmenu
```

... and placing the contents of this repository into .config/awesome. If using ohmyzsh, set a custom path for orbital.zsh-theme.

Optional extras:

**mononoki** used as a global font.

**picom** for transparency (spawned with awesome)

**feh** for background (spawned with awesome, will pick random image in /Pictures/wallpapers by default.

**alacritty** as default terminal.

**neovim** as default editor.

**theme.sh** will randomise terminal theme on startup, provided ohmyzsh is installed and theme memory is set up.
