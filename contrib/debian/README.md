
Debian
====================
This directory contains files used to package searchcoind/searchcoin-qt
for Debian-based Linux systems. If you compile searchcoind/searchcoin-qt yourself, there are some useful files here.

## searchcoin: URI support ##


searchcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install searchcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your searchcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/searchcoin128.png` to `/usr/share/pixmaps`

searchcoin-qt.protocol (KDE)

