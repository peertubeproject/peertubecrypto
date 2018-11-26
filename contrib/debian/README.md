
Debian
====================
This directory contains files used to package peertubed/peertube-qt
for Debian-based Linux systems. If you compile peertubed/peertube-qt yourself, there are some useful files here.

## peertube: URI support ##


peertube-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install peertube-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your peertubeqt binary to `/usr/bin`
and the `../../share/pixmaps/peertube128.png` to `/usr/share/pixmaps`

peertube-qt.protocol (KDE)

