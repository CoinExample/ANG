
Debian
====================
This directory contains files used to package angd/ang-qt
for Debian-based Linux systems. If you compile angd/ang-qt yourself, there are some useful files here.

## ang: URI support ##


ang-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ang-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ang-qt binary to `/usr/bin`
and the `../../share/pixmaps/ang128.png` to `/usr/share/pixmaps`

ang-qt.protocol (KDE)

