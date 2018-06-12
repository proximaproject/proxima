
Debian
====================
This directory contains files used to package proximad/proxima-qt
for Debian-based Linux systems. If you compile proximad/proxima-qt yourself, there are some useful files here.

## proxima: URI support ##


proxima-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install proxima-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your proxima-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

proxima-qt.protocol (KDE)

