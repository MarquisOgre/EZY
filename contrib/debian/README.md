
Debian
====================
This directory contains files used to package eazyd/eazy-qt
for Debian-based Linux systems. If you compile eazyd/eazy-qt yourself, there are some useful files here.

## eazy: URI support ##


eazy-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eazy-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eazyqt binary to `/usr/bin`
and the `../../share/pixmaps/eazy128.png` to `/usr/share/pixmaps`

eazy-qt.protocol (KDE)

