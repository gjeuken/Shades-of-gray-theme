# Shades-of-gray

Shades-of-gray is a flat dark GTK-theme with ergonomic contrasts. It supports Gnome, Cinnamon, Xfce4, Mate and Openbox.
Theme customizations for Firefox, Thunderbird and Inkscape are additionally included.
Shades-of-gray is available in seven color variants:

<p align="center">
<img src="https://user-images.githubusercontent.com/22373662/46028563-3db93780-c0f1-11e8-85e5-e04d68cb615b.png" width="60%"></img></br><i>Gray, Arch, Cerulean, Firebrick, Harvest, Orient, Patina</i>
</p>

## Installation

### Arch Linux

You can install the AUR package:
* Last release: [gtk-theme-shades-of-gray](https://aur.archlinux.org/packages/gtk-theme-shades-of-gray)
* Git version: [gtk-theme-shades-of-gray-git](https://aur.archlinux.org/packages/gtk-theme-shades-of-gray-git)

### Installation via terminal

You can install the git version by using this method:

```
mkdir ~/Shades-of-gray-git
cd ~/Shades-of-gray-git/
git clone https://github.com/WernerFP/Shades-of-gray-theme.git
cd Shades-of-gray-theme/
rm -rf README.md LICENSE .git
sudo cp -r * /usr/share/themes/
```
Existing installations of Shades-of-gray are overwritten by the last command. If Shades-of-gray was previously installed using your distribution‘s package management, the package should be uninstalled first.

### Manual Installation

Copy the chosen theme folders either for personal use into directory `~/.themes/` or for common use into `/usr/share/themes/`.

## Gadgets

Each theme folder contains an `app-gadgets` directory with additional theme files for Thunderbird, Firefox and Inkspape.

### Thunderbird

The folder `assets` and the file `userChrome.css` in folder `Thunderbird-Shades-of-gray` contain a Thunderbird theme adapted to Shades of gray. Copy both to this location:
```
~/.thunderbird/<name-of-your-profile>/chrome/assets
~/.thunderbird/<name-of-your-profile>/chrome/userChrome.css
```
Lightning uses its own bright colors in default setting. The option for using theme colors is hidden as *Accessibility*. Open the Thunderbird settings and activate the checkbox *Optimize colors for accessibility* in calendar area.

If you change a Shades-of-gray theme color, it is not necessary to copy the file again. You can simply comment out the current theme color in `userChrome.css` (Thunderbird and/or Firefox) uncomment the new theme color value.

### Firefox

The file `userChrome.css` in folder `Firefox-Shades-of-gray` contains a theme adaptation to Shades-of-gray. To enable the customizations, copy the file or its content to this location:

`~/.mozilla/firefox/<name-of-your-profile>/chrome/userChrome.css`

Firefox uses widgets of the current GTK3 theme in websites that have not designed their own widgets for forms. With dark themes this is ugly and input fields, checkboxes etc. are difficult to use (e.g. black font in dark input fields). To fix this behavior the file `userContent.css` contains color-neutral form widgets.

This file also contains theme customizations for the New Tab page (*about:newtab*).

Copy the file or its contents to this location for enabling:

`~/.mozilla/firefox/<name-of-your-profile>/chrome/userContent.css`

Note: You should choose the dark style in Firefox to get a consistent dark appearance.

#### Firefox add-ons

##### Bookmark search plus 2
The file `bookmark-search-plus-2.css` contains theme customizations for the very useful add-on *Bookmark search plus 2* ([AMO](https://addons.mozilla.org/firefox/addon/bookmark-search-plus-2) | [Github](https://github.com/aaFn/Bookmark-search-plus-2)). Copy this file in addition to `userContent.css` into your *chrome* directory:

`~/.mozilla/firefox/<name-of-your-profile>/chrome/bookmark-search-plus-2.css`

##### Panorama Tab Groups
The file `panorama-tab-groups.css` contains theme customizations for the recommended add-on *Panorama Tab Groups* ([AMO](https://addons.mozilla.org/firefox/addon/panorama-tab-groups) | [Github](https://github.com/projectdelphai/panorama-tab-groups)). Copy this file in addition to `userContent.css` into your *chrome* directory:

`~/.mozilla/firefox/<name-of-your-profile>/chrome/panorama-tab-groups.css`

Note: In *Panorama Tab Groups* you can toggle between light and dark theme. The Shades-of-gray customizations only take effect with the dark theme.

### Inkscape

Original colored icons in Inkscape are hard to identify in dark themes. The file `icon.svg` in folder `Inkscape-icons` contains bright icons.
To use them in Inkscape, the file must be stored in this directory:

`~/.config/inkscape/icons/icons.svg`

## Requirements

* GTK+ 3.20 or above
* Pixmap theme engine
* Murrine theme engine

## License:

GPL-3.0+

## Screenshots

Cinnamon Patina, Gnome Gray,</br>
Openbox Arch, Xfce4 Cerulean
<p align="center">
<img src="https://user-images.githubusercontent.com/22373662/46028566-414cbe80-c0f1-11e8-96d5-0525cfe93555.png" width="45%"></img>  <img src="https://user-images.githubusercontent.com/22373662/46028571-44e04580-c0f1-11e8-87f9-43d35967a6df.png" width="45%"></img>  <img src="https://user-images.githubusercontent.com/22373662/46028577-4873cc80-c0f1-11e8-9eb2-25f41528bc9b.png" width="45%"></img>  <img src="https://user-images.githubusercontent.com/22373662/46028583-4d388080-c0f1-11e8-8fbe-77b6744ce813.png" width="45%"></img>
</p>