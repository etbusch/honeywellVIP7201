# honeywellVIP7201
Termcap and terminfo files for the Honeywell VIP 7201 Serial Terminal

![](https://i.imgur.com/SSkMy1O.jpg)

This is compatible with most versions of ncurses and similar libraries that need specific terminal handling for a serial terminal this old. Beware though, that several more modern programs ignore the global terminal environment variable and just assume you're on xterm or a similar emulator.

On the Honeywell VIP 7200 Series terminals, the following configuration string works well, though this has the AUX port disabled, so modify at your leisure.

0110 1000 1010 0110 0111 1000 1001 0001 0010

Let me know if you have any improvements, feel free to submit a pull request!


