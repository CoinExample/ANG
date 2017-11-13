
Debian
====================
This directory contains files used to package ANGd/ANG-qt
for Debian-based Linux systems. If you compile ANGd/ANG-qt yourself, there are some useful files here.

## ANG: URI support ##


ANG-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ANG-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ANG-qt binary to `/usr/bin`
and the `../../share/pixmaps/ANG128.png` to `/usr/share/pixmaps`

ANG-qt.protocol (KDE)

