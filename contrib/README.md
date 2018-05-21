
Debian
====================
This directory contains files used to package spectord/spector-qt
for Debian-based Linux systems. If you compile spectord/spector-qt yourself, there are some useful files here.

## spector: URI support ##


spector-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install spector-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your spectorqt binary to `/usr/bin`
and the `../../share/pixmaps/spector128.png` to `/usr/share/pixmaps`

spector-qt.protocol (KDE)

