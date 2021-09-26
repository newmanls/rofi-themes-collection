# Themes Collection for Rofi Launcher

## What is Rofi?

Rofi is A window switcher, Application launcher and dmenu replacement.
Rofi started as a clone of simpleswitcher and It has been extended with extra features,
like an application launcher and ssh-launcher, and can act as a drop-in dmenu replacement,
making it a very versatile tool. Rofi, like dmenu, will provide the user with a textual list of
options where one or more can be selected. This can either be running an application, selecting
a window, or options provided by an external script. You can learn more about Rofi [here](https://github.com/davatorium/rofi).

## Screenshots

### Launchpad
![launchpad](screenshots/screenshot_launchpad.png)

### Nord
![nord](screenshots/screenshot_nord.png)

### Nord (oneline)
![nord-oneline](screenshots/screenshot_nord-oneline.png)

### Nord (two lines)
![nord-twoLines](screenshots/screenshot_nord-twoLines.png)

### Rounded
![rounded-blue-dark](screenshots/screenshot_rounded-blue-dark)
![rounded-gray-dark](screenshots/screenshot_rounded-gray-dark)
![rounded-green-dark](screenshots/screenshot_rounded-green-dark)
![rounded-orange-dark](screenshots/screenshot_rounded-orange-dark)
![rounded-pink-dark](screenshots/screenshot_rounded-pink-dark)
![rounded-purple-dark](screenshots/screenshot_rounded-purple-dark)
![rounded-red-dark](screenshots/screenshot_rounded-red-dark)
![rounded-yellow-dark](screenshots/screenshot_rounded-yellow-dark)

### Spotlight (light)
![spotlight](screenshots/screenshot_spotlight.png)

### Spotlight (dark)
![spotlight-dark](screenshots/screenshot_spotlight-dark.png)

### Squared Everforest
![squared-nord](screenshots/screenshot_squared-everforest.png)

### Squared Nord
![squared-nord](screenshots/screenshot_squared-nord.png)

### Squared Material Red
![squared-material-red](screenshots/screenshot_squared-material-red.png)

## Don't have rofi yet? Install it!

- On Debian / Ubuntu : `apt-get install rofi`
- On Arch / Arch-based : `pacman -S rofi`
- On Fedora : `dnf install rofi`

> You can learn how to set Rofi shortcuts and more [here.](https://github.com/davatorium/rofi)

## Installing themes

1. Clone this repository and change to its directory:
```
$ git clone https://github.com/lr-tech/rofi-themes-collection.git
$ cd rofi-themes-collection
```

2. If you don't have the directories needed for the install create them with:
```
$ mkdir -p ~/.local/share/rofi/themes/
```

3. Copy your desired theme to `~/.local/share/rofi/themes` folder:
```
$ cp themes/<your-selected-theme> ~/.local/share/rofi/themes/
```

4. Run Rofi in `run` modi, then run `rofi-theme-selector`.

5. Search for your desired theme, press `enter` to preview, then `Alt+a` to accept the new theme.

6. Enjoy your new Rofi theme!

