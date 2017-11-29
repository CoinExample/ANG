
Debian
====================
This directory contains files used to package coinnamed/coinname-qt
for Debian-based Linux systems. If you compile coinnamed/coinname-qt yourself, there are some useful files here.

## coinname: URI support ##


coinname-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install coinname-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your coinname-qt binary to `/usr/bin`
and the `../../share/pixmaps/coinname128.png` to `/usr/share/pixmaps`

coinname-qt.protocol (KDE)

