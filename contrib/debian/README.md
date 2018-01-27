
Debian
====================
This directory contains files used to package paradigmd/paradigm-qt
for Debian-based Linux systems. If you compile paradigmd/paradigm-qt yourself, there are some useful files here.

## paradigm: URI support ##


paradigm-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install paradigm-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your paradigm-qt binary to `/usr/bin`
and the `../../share/pixmaps/paradigm128.png` to `/usr/share/pixmaps`

paradigm-qt.protocol (KDE)

