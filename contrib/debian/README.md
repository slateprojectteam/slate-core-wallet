
Debian
====================
This directory contains files used to package slcd/slc-qt
for Debian-based Linux systems. If you compile slcd/slc-qt yourself, there are some useful files here.

## slc: URI support ##


slc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install slc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your slcqt binary to `/usr/bin`
and the `../../share/pixmaps/slc128.png` to `/usr/share/pixmaps`

slc-qt.protocol (KDE)

