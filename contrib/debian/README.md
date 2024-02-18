
Debian
====================
This directory contains files used to package CATSd/CATS-qt
for Debian-based Linux systems. If you compile CATSd/CATS-qt yourself, there are some useful files here.

## pivx: URI support ##


CATS-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install CATS-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your CATS-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

CATS-qt.protocol (KDE)

