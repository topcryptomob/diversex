
Debian
====================
This directory contains files used to package diversexd/diversex-qt
for Debian-based Linux systems. If you compile diversexd/diversex-qt yourself, there are some useful files here.

## diversex: URI support ##


diversex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install diversex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your diversexqt binary to `/usr/bin`
and the `../../share/pixmaps/diversex128.png` to `/usr/share/pixmaps`

diversex-qt.protocol (KDE)

