
Debian
====================
This directory contains files used to package smartcloudd/smartcloud-qt
for Debian-based Linux systems. If you compile smartcloudd/smartcloud-qt yourself, there are some useful files here.

## smartcloud: URI support ##


smartcloud-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install smartcloud-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your smartcloudqt binary to `/usr/bin`
and the `../../share/pixmaps/smartcloud128.png` to `/usr/share/pixmaps`

smartcloud-qt.protocol (KDE)

