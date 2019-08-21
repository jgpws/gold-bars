# GoldBars
GoldBars is a collection of GTK based themes with gold coloring and 3-dimensional icons. The package includes GTK2, GTK3, Metacity, XFWM and Openbox themes.

* [Theme Homepage](https://www.jasong-designs.com/2018/10/05/goldbars/)

## How to Install

1. Download the latest file from the [downloads](https://github.com/jgpws/gold-bars/tree/master/downloads) directory
2. Open a Terminal application
3. Navigate to your Downloads folder in the terminal (usually titled Downloads). Type `cd Downloads`
4. Type `ls` and look for `gold-bars-MM-DD-YY.tar.gz`, where month, day and year represent when the file was last updated
5. Untar the file by typing `tar -zxvf gold-bars-01-01-17.tar.gz`, substituting the current version's date numbers
6. type `cd` again to get to your home folder; type `ls -a` and see if there is a **.themes** directory
7. If one does not exist, create one: `mkdir .themes`
8. `cd Downloads`
9. `cp GoldBars ../.themes`

### To Install GoldBars Globally

1. Follow steps 1-5 above
2. `cd /usr/share/themes`
3. `sudo cp -r ~/Downloads/JGD-Black /usr/share/themes`
4. Enter sudo password
5. `ls` to check that the theme folder is present

### To Install on Arch Linux:

GoldBars can be found in the Arch User Repository. To install, you can use an AUR helper:

`yay -S goldbars`

## After Installation

Once installed, you can use a theme switching application such as **LXAppearance** or **Gnome Tweak Tool** to change the theme to GoldBars.

### Metacity

You can switch the Metacity theme from the command line:

`gsettings set org.gnome.desktop.wm.preferences theme GoldBars`

The above setting worked in a Compiz environment in Arch. For other desktop environments, see the article [Gnome Appearance modify command in Linux / How to change theme using command line in GNOME](http://www.pc-freak.net/blog/gnome-appearance-modify-command-in-linux-how-to-change-theme-using-command-line-in-gnome/).

## How to Install the Required Theme Engines

The latest GTK2 version of GoldBars requires the Murrine and Pixmap theme engines. To install:
### Ubuntu and derivatives:
`sudo apt-get install gtk2-engines-murrine`

`sudo apt-get install gtk2-engines-pixbuf`
### ArchLinux and derivatives:
`sudo pacman -S gtk-engine-murrine`

`sudo pacman -S gtk-engines`

Note: The GTK3 version of this theme only works in version 3.20 and upwards.
