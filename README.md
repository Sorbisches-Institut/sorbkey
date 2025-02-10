# sorbkey
Provide simple xkb keyboard layout for Sorbian languages Upper Sorbian (hsb) and Lower Sorbian (dsb) for Linux/X11 (e.g Ubuntu desktop).  It is based on the German keyboard. 

It simply adds the keystrokes to get Sorbian characters with caron sign + base letter (e.g. č,ž,š,ě,ř) using circumflex (dead) key (keycode TLDE). 
Use acute/accent key to get the diacritics with acute (ć,ź,ś,ó,ŕ,ń). The lstroke (ł/Ł) character is placed on "l/L" using AltGr.


### Simple installation to use
copy <i>hsb</i> or <i>dsb</i> file to <i>/usr/share/X11/xkb/symbols</i>

run <i>setxkbmap hsb</i> or <i>setxkbmap dsb</i> in the bash


### Advanced installation for selection on Region&Languages / Input Sources
tbd.
