
Debian
====================
This directory contains files used to package compassd/compass-qt
for Debian-based Linux systems. If you compile compassd/compass-qt yourself, there are some useful files here.

## compass: URI support ##


compass-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install compass-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your compass-qt binary to `/usr/bin`
and the `../../share/pixmaps/compass128.png` to `/usr/share/pixmaps`

compass-qt.protocol (KDE)

