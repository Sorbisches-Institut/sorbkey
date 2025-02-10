# sorbkey
Provide simple xkb keyboard layout for Sorbian languages Upper Sorbian (hsb) and Lower Sorbian (dsb) for Linux/X11 (e.g Ubuntu desktop)
It is based on the German keyboard. It simply adds the keystrokes to get Sorbian characters with caron sign + base letter (e.g. č,ž,š,ě,ř) using circumflex (dead) key (keycode TLDE). Use acute/accent key to get the accute + base letters (ć,ź,ś,ó,ŕ,ń). The lstroke character (ł/Ł) is placed on "l" using AltGr.


# the simple installation and use - switch current keyboard
copy hsb or dsb to /usr/share/X11/xkb/symbols
run "setxkbmap hsb" or "setxkbmap dsb" in the bash
