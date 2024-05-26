## Linux config files

Backup .bashrc file for terminal
Backup synth shell for terminal

## Custom i3 Window Manager Config

I3 is a tiling window manager that is inspired from WMII that is primarily targeted to developers. 

Its targeted mainly for platforms that are GNU/Linux and BSD OS. The code is Open Source and its under BSD license.

It can be used as a tree data strucutre. It allows flexible layouts. It has multiple keybinding that can resize the windows and you can use VIM or nano to edit the config file.

In config file you can define the styling of the bar, windows, what and how many windows will be opened up on boot or initializazion, you can define how many window enviroments you can have etc..


## Install packages
These packages are mainly from Ubuntu/Debian.

```bash
# install i3-wm and its required packages
sudo apt install xorg lightdm lightdm-gtk-greeter i3-wm i3lock i3status i3blocks dmenu terminator

# Feh or Nitrogen for Wallpaper
sudo apt-get -y install nitrogen
sudo apt-get feh

#tty-clock
sudo apt-get install tty-clock

# Btop for diagnostics
sudo apt-get install btop

# Installing new theme or icons
sudo apt install lxappearance

# Transparent terminal 
sudo apt install picom

# Cross-platform Audio Visualizer
sudo apt install build-essential libfftw3-dev libasound2-dev libncursesw5-dev libpulse-dev libtool automake autoconf-archive libiniparser-dev libsdl2-2.0-0 libsdl2-dev libpipewire-0.3-dev libjack-jackd2-dev pkgconf

sudo apt install cava

```
