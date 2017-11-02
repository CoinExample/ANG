
Debian
====================
This directory contains files used to package dragoncoind/dragoncoin-qt
for Debian-based Linux systems. If you compile dragoncoind/dragoncoin-qt yourself, there are some useful files here.

## dragoncoin: URI support ##


dragoncoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dragoncoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dragoncoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/dragoncoin128.png` to `/usr/share/pixmaps`

dragoncoin-qt.protocol (KDE)

