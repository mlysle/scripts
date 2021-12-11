# Scripts

## newscratch
A scratchwindow manager for [bspwm](https://github.com/baskerville/bspwm).

###Usage:
1. Add the following to your bspwmrc file:	
	bspc rule -a dropdown sticky=on state=floating center=on rectangle=1000x800+0+0
2. Add newscratch keybinds to your window manager.

## search
Browser-independent search utility using dmenu and wmctrl .

###Usage examples:
* "wt query" - searches wiktionary for the definition of *query* in English.
* "wt la iam" - searches wiktionary for the definition of *iam* in Latin.
* "a fstab" - searches the Arch Linux Wiki for articles about fstab.
* "i linux" - searches my [invidious](https://invidious.lysle.org) instance for videos about Linux.
* "d thinkpad" - searches DuckDuckGo for the "thinkpad".
