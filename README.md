# ConEmu i3 Config

A ConEmu configuration script which approximates i3 window manager keybindings.

## Key bindings

| Action                                     | Key                  |
|--------------------------------------------|----------------------|
| Create new split (horizontally/vertically) | LAlt+(H/V)           |
| Focus console (left/down/up/right)         | LAlt+(J/K/L/;)       |
| Grow/shrink current split                  | LAlt+LCtrl+(J/K/L/;) |
| Kill current process (violently)           | LCtrl+X              |
| Close current console (violently)          | LAlt+LShift+Q        |
| Close current console (gently)             | LCtrl+W              |
| Toggle maximise current console            | LAlt+F               |
| New Tab                                    | LCtrl+T              |
| Switch to Tab                              | LAlt+(0-9)           |
| Exit                                       | LAlt+LShift+E        |

## Limitations

* There is no way to move a console.
* Growing/shrinking behaviour may not be identical to i3.
* Creating a new horizontal/vertical split is immediate (There is no Alt+Enter combination like in i3).
* Tab numbers are incremented based on the number of consoles which does not match the i3 workspace numbering system.

## Other changes

Some visual and functional configuration changes were made to make ConEmu behave more like i3.

## Installation Guide

* Launch ConEmu
* Click the hamburger menu
* Click Settings
* Click Main
* Click Import
* Import the conemu.xml file from this repository. This will overwrite all existing settings.

## Resources

* [i3 key bindings reference card](https://i3wm.org/docs/refcard.html)
* [i3 key bindings](https://i3wm.org/docs/userguide.html#_default_keybindings)
* [ConEmu GuiMacros](https://conemu.github.io/en/GuiMacro.html)
* [ConEmu Tasks](https://conemu.github.io/en/Tasks.html)

