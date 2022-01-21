Debian
======

This directory contains files used to package cougard/cougar-qt
for Debian-based Linux systems. If you compile cougard/cougar-qt yourself, there are some useful files here.

## cougar: URI support ##

cougar-qt.desktop (Gnome / Open Desktop)

To install:

	sudo desktop-file-install cougar-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cougar-qt binary to `/usr/bin`
and the `../../share/pixmaps/cougar128.png` to `/usr/share/pixmaps`

cougar-qt.protocol (KDE)