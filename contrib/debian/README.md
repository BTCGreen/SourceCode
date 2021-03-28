
Debian
====================
This directory contains files used to package greenbitcoind/greenbitcoin-qt
for Debian-based Linux systems. If you compile greenbitcoind/greenbitcoin-qt yourself, there are some useful files here.

## greenbitcoin: URI support ##


greenbitcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install greenbitcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your greenbitcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/greenbitcoin128.png` to `/usr/share/pixmaps`

greenbitcoin-qt.protocol (KDE)

