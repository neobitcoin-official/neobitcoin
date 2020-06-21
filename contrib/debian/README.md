
Debian
====================
This directory contains files used to package neobitcoind/neobitcoin-qt
for Debian-based Linux systems. If you compile neobitcoind/neobitcoin-qt yourself, there are some useful files here.

## neobitcoin: URI support ##


neobitcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install neobitcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your neobitcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/neobitcoin128.png` to `/usr/share/pixmaps`

neobitcoin-qt.protocol (KDE)

