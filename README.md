# CyvoIcons

An Adwaita styled theme with extra icons for popular apps to complement Gnome Shell's original icons.
The purpose of this theme is to provide a consistent look and feel with Gnome Shell's design.

The purpose of CyvoIcons is to add to Adwaita, not modify it, and to do roughly what Breeze does for KDE. This theme does not override any Adwaita icons, nor any Gnome Circle apps icons, nor icons that generally fit into the Adwaita paradigm (like Transmission GTK).

This theme is built and tested against vanilla Gnome on Arch Linux. If an icon is in the theme, but is not applying to your app, please open an issue and mention the icon name referenced in your app's `.desktop` file.

## Installation

#### Download the theme

`git clone https://github.com/ehte92/CyvoIcons.git`

#### Install for local user

`cp -r CyvoIcons/ ~/.local/share/icons/`

#### Install system-wide

`sudo cp -r CyvoIcons/ /usr/share/icons/`

## Activation

Either use the `Tweaks` app to choose and activate the icon theme or run the following command:

`gsettings set org.gnome.desktop.interface icon-theme 'CyvoIcons'`

#### Troubleshooting

If the theme doesn't apply try the following command:

##### For local installation

`gtk-update-icon-cache -f -t ~/.local/share/icons/CyvoIcons && xdg-desktop-menu forceupdate`

##### For system-wide installation

`sudo gtk-update-icon-cache -f -t /usr/share/icons/CyvoIcons && xdg-desktop-menu forceupdate`
