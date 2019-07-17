# us_uml

US Keyboard layout with umlauts via AltGr for X11

Created with [keyboardlayouteditor](https://github.com/simos/keyboardlayouteditor)

Inspired by https://hci.rwth-aachen.de/usgermankeyboard

## Setup

* copy `us_uml` to `/usr/share/X11/xkb/symbols`
* add content of `evdev.xml` (without `...` and `</layoutList>`) to `/usr/share/X11/xkb/rules/evdev.xml` right before `</layoutList>`
* Reboot
* Search for keyboard layout "US with umlauts via AltGr" (English)
