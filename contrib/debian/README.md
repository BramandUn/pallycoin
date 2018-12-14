
Debian
====================
This directory contains files used to package pallycoind/pallycoin-qt
for Debian-based Linux systems. If you compile pallycoind/pallycoin-qt yourself, there are some useful files here.

## pallycoin: URI support ##


pallycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pallycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pallycoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/pallycoin128.png` to `/usr/share/pixmaps`

pallycoin-qt.protocol (KDE)

