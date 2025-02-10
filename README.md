# sorbkey
Provide simple xkb keyboard layout for Sorbian languages Upper Sorbian (hsb) and Lower Sorbian (dsb)
It is based on the German keyboard. It simply adds the keystrokes to get Sorbian characters with caron+base letter using circumflex dead key (keycode TLDE).
The lstroke character (ł/Ł) is put on "l" using AltGr.


# the simple use - switch current kee
copy hsb or dsb to /usr/share/X11/xkb/symbols
run "setxkbmap hsb" or "setxkbmap dsb" in the bash
