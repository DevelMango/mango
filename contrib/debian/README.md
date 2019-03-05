Debian
======

This directory contains files used to package mangod/mango-qt
for Debian-based Linux systems. If you compile mangod/mango-qt yourself, there are some useful files here.

## mango: URI support ##

mango-qt.desktop (Gnome / Open Desktop)

To install:

	sudo desktop-file-install mango-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mango-qt binary to `/usr/bin`
and the `../../share/pixmaps/mango128.png` to `/usr/share/pixmaps`

mango-qt.protocol (KDE)