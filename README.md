# Blue Mood for eDEX UI

An implementation of [emacs's Blue Mood theme's](https://emacsthemes.com/themes/blue-mood-theme.html) colors for [eDEX UI](https://github.com/GitSquared/edex-ui).

# Screenshots

### Regular Blue Mood

![Screenshot](https://raw.githubusercontent.com/blue-mood/blue-mood-everything/master/screenshots/blue-mood-edex-screenshot.png)

### Blue Mood fulltype
(keyboard occupies entire bottom half of screen)

![Fulltype Screenshot](https://raw.githubusercontent.com/blue-mood/blue-mood-everything/master/screenshots/blue-mood-fulltype-edex-screenshot.png)

### Blue Mood notype
(keyboard is hidden, file pane occupies entire bottom half of screen)

![Notype Screenshot](https://raw.githubusercontent.com/blue-mood/blue-mood-everything/master/screenshots/blue-mood-notype-edex-screenshot.png)

# Installation

Place the files in your [`"UserData"/themes`](https://github.com/GitSquared/edex-ui/wiki/userData) folder (e.g. `$XDG_CONFIG_HOME/eDEX-UI/themes` or `~/.config/eDEX-UI/themes` for Linux, `%APPDATA%\eDEX-UI\themes` for Windows).

# Activation

Choose from the following methods:

- [Access the settings panel from inside eDEX UI](https://github.com/GitSquared/edex-ui/wiki/settings.json) (either by double-clicking the `settings.json` file in the file pane or by using the `CommandOrCtrl+Shift+S` keyboard shortcut) and choose the desired theme. Afterwards, `Save to Disk` and `Reload UI` so that the change will take effect.
- Double-click the desired theme from the themes folder in the file pane inside eDEX UI ([the change will not be saved to the settings in this case though](https://github.com/GitSquared/edex-ui/wiki/Themes)).
- Before launching eDEX UI, manually edit settings.json with an external editor and type the name of the desired theme in the "theme" field.
