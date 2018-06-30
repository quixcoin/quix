
Debian
====================
This directory contains files used to package quixd/quix-qt
for Debian-based Linux systems. If you compile quixd/quix-qt yourself, there are some useful files here.

## quix: URI support ##


quix-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install quix-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your quix-qt binary to `/usr/bin`
and the `../../share/pixmaps/quix128.png` to `/usr/share/pixmaps`

quix-qt.protocol (KDE)

