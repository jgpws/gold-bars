In order to view the GTK3 theme in applications like A Widget Factory, which only recognizes a gtk-3.0 directory, just create a symbolic link to the gtk-3.20 directory.

ln -s gtk-3.20 gtk-3.0

or if installed in /usr/share/themes,

sudo ln -s gtk-3.20 gtk-3.0
