

This desktop is heavily inspired and created on Archcraft(archcraft-os.github.io). Its a great minimal arch based distro with a gorgeous desktop.

Steps to get my Desktop:

1) Install the following dependencies(If you want updates to your terminal, replace termite with alacritty or kitty as termite is obsolete now)
yay -S Openbox BSPWM polybar rofi dunst mpd ncmpcpp dmenu geany obmenu-generator ranger termite compton zsh oh-my-zsh nitrogen lxappearance
(If you use a different AUR helper like paru , please use it accordingly. I am using the AUR to install most of the packages as some of the patched packages are not available in the official repos)

2) Move Backgrounds folder to /usr/share/backgrounds

3) Move Themes folder to /usr/share/themes

4) Move icons folder to /usr/share/icons

5) Move everything else but the .config folder to your home directory

6) Copy the contents of the .config folder and paste them in ~/.config/

7) Some of the fonts to install- Fira mono for powerline, Cascadia code, iosevka nerd font, Dejavu sans, Source code pro(Or copy the contents of the fonts folder and paste it in /usr/share/fonts)

8) Copy the contents of bin and paste them in /usr/bin

9) Copy the archlabs folder and paste it in /usr/lib

10) That's it! you should be good to go now. Reboot once just to be safe and login to your new system
