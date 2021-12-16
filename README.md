# Scripts

## newscratch
A scratchwindow manager for [bspwm](https://github.com/baskerville/bspwm).
### Demo:
![scratchpads](scratchpads.gif)
### Usage:
1. Add the following rule to your bspwmrc config file:	
```
bspc rule -a dropdown layer=above sticky=on state=floating center=on rectangle=1000x800+0+0
```
2. Add newscratch keybinds to your window manager. Usage: newscratch [program]. That's it!

## newsearch
Browser-independent search utility using dmenu and wmctrl.

### Usage examples:
* "wt query" - searches wiktionary for the definition of *query* in English.
* "wt la iam" - searches wiktionary for the definition of *iam* in Latin.
* "a fstab" - searches the Arch Linux Wiki for articles about fstab.
* "i linux" - searches [invidious.lysle.org](https://invidious.lysle.org) for videos about Linux.
* "d thinkpad" - searches DuckDuckGo for "thinkpad".
