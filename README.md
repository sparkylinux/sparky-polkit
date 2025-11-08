Sparky Polkit
The script starts gnome-polkit or lxpolkit in window managers
installed via APTus Desktop, Minimal ISO and so.
Supported desktops: awesome, bspwm, enlightenment, fluxbox, i3,
icewm, jwm, manokwari, openbox, pekwm, twin (trinity), window maker.

Copyright (C) 2017-2025 Paweł Pijanowski

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Dependencies:
-------------
coreutils
lxpolkit | policykit-1-gnome
sysvinit-utils

Install:
-------------
su (or sudo) 
./install.sh

Uninstall:
-------------
su (or sudo)
./install.sh uninstall
