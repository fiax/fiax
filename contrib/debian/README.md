
Debian
====================
This directory contains files used to package fiaxd/fiax-qt
for Debian-based Linux systems. If you compile fiaxd/fiax-qt yourself, there are some useful files here.

## fiax: URI support ##


fiax-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fiax-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fiaxqt binary to `/usr/bin`
and the `../../share/pixmaps/fiax128.png` to `/usr/share/pixmaps`

fiax-qt.protocol (KDE)

