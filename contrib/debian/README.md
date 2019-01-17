
Debian
====================
This directory contains files used to package CoinAlpacad/CoinAlpaca-qt
for Debian-based Linux systems. If you compile CoinAlpacad/CoinAlpaca-qt yourself, there are some useful files here.

## CoinAlpaca: URI support ##


CoinAlpaca-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install CoinAlpaca-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your CoinAlpacaqt binary to `/usr/bin`
and the `../../share/pixmaps/CoinAlpaca128.png` to `/usr/share/pixmaps`

CoinAlpaca-qt.protocol (KDE)

