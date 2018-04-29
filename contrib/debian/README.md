
Debian
====================
This directory contains files used to package roxyd/roxy-qt
for Debian-based Linux systems. If you compile roxyd/roxy-qt yourself, there are some useful files here.

## roxy: URI support ##


roxy-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install roxy-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your roxyqt binary to `/usr/bin`
and the `../../share/pixmaps/roxy128.png` to `/usr/share/pixmaps`

roxy-qt.protocol (KDE)

