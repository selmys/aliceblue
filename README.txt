Running Aliceblue Under Linux
=============================

Aliceblue should run on most Linux distributions providing they meet 
the following criteria:

0. You should be running the Gnome desktop.
1. The display server should be X11.org and not Wayland. 
   You can check this by entering this command in a terminal window:
        echo $XDG_SESSION_TYPE
   and it should display x11
2. You should have the following packages installed:
    On Ubuntu-type systems enter the following:
        sudo apt-get install xterm dconf vorbis-tools wmctrl
    On Fedora-type systems enter the following:
        sudo dnf install xterm dconf vorbis-tools wmctrl
3. You also need to adjust your gnome terminal preferences:
    Under TEXT select custom font and set it to Monospace Regular 14
    Under COLOURS uncheck "Use colours from system theme" and
                  uncheck "Use transparency from system theme"
4. Adjust your sound volume.
5. Download and unzip Aliceblue.zip
6. Change to the Alice directory (cd Alice) and enter this command:
        ./aliceblue 12
    where 12 is the font size you wish to use.

