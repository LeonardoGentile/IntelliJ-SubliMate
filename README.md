IntelliJ-Sublimate
==================

A (sane) Sublime / TextMate inspired keymap for IntelliJ12

## Notes

* I haven't tested this on previous versions of IntelliJ
* Keymap only setup for OSX at this time
* Color Scheme `colors/SubliMate.xml` is optional and simply adds a line highlight to the default theme **Darcula**

![SubliMate Color Scheme Screenshot](https://raw.github.com/ProLoser/IntelliJ-Sublimate/master/screenshot.png)


## Installation

### Import

Original project:
File > Import Settings > [[Select SubliMate.jar](https://github.com/ProLoser/IntelliJ-Sublimate/raw/master/SublimMate.jar)]
_-- or --_ my customized version:
File > Import Settings > [[Select LeoMate.jar](https://github.com/LeonardoGentile/IntelliJ-SubliMate/raw/master/LeoMate.jar)]

_-- or --_

Copy the `SubliMate.xml` files to their respective directories in `~/Library/Preferences/IntelliJIdea12`

### Enable

Settings > Keymap > Keymaps: [Select LeoMate]

Settings > Editor > Colors & Fonts > Scheme name: [Select LeoMate]  (Tweaked Twilight Dark)

## Shortcuts

I've mixed together some Sublime and TextMate shortcuts, occasionally breaking IntelliJ shortcuts when necessry. Feel free to fork and help make a better overall collection of shortcuts!

* Open File - ⌘P
* Find Function - ⌘R or ⌘⇧O
* Find - ⌘F
* Find in Path - ⌘⇧F
* Replace - ⌘R or ⌘⌥F
* Replace in Path - ⌘⇧R or ⌘⌥F
* Close Tab - ⌘W
* Reopen Tab - ⌘⇧W
* Close All Tabs - ⌘⌥W
* Close All Other Tabs - ⌘⇧⌥W
* Find Action (Quick Command Palette) - ⌘⇧P
* Wrap (contents in...) - ⇧^W
* Duplicate Lines (⌘D removed) - ⌘⇧D
* Delete Line - ⌘K
* Go To Next Match Found (while searching) - ⌘G
* Go To Previous Match Found (while searching) - ⌘⇧G
* Go To Line Number - ^G or ⌘L
* others I'm probably forgetting

I removed ⌘⇧M so that I could reuse it for my system-wide Zoom shortcut
