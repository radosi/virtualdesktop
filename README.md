# FORK of windows-desktop-switcher
An AutoHotkey script for Windows that lets a user switch virtual desktops by pressing <kbd>CapsLock</kbd> and a number row key at the sime time (e.g. <kbd>CapsLock</kbd> + <kbd>2</kbd> to switch to Desktop 2). It also provides other features, such as customizing the key combinations, creation/deletion of desktops by hotkey, etc. (see Hotkeys section below).

## Hotkeys

Action | Keys 
--- | :-:
**Switch** to virtual desktop **1, 2, etc.**<br>*(you can also use the Numpad)*|<kbd>CapsLock</kbd> + <kbd>1</kbd><br><kbd>CapsLock</kbd> + <kbd>2</kbd><br>...<br><kbd>CapsLock</kbd> + <kbd>0</kbd>
**Current virtual desktop ID 1 - 10** to the last desktop used|<kbd>CapsLock</kbd> + <kbd>`</kbd>
**Move** the current window to another desktop, then switch to it<br>*Keys <kbd>Q</kbd>, <kbd>W</kbd>, etc. correspond to **1st, 2nd, etc.** desktops*|<kbd>CapsLock</kbd> + <kbd>Q</kbd><br><kbd>CapsLock</kbd> + <kbd>W</kbd><br>...<br><kbd>CapsLock</kbd> + <kbd>P</kbd>
Home, End, Page Up, Page Down, Del |<kbd>CapsLock</kbd> + <kbd>←</kbd><br><kbd>CapsLock</kbd> + <kbd>→</kbd><br><kbd>CapsLock</kbd> + <kbd>↑</kbd><br><kbd>CapsLock</kbd> + <kbd>↓</kbd><br><kbd>CapsLock</kbd> + <kbd>backspace</kbd>

You can also customize the hotkeys and actions as described in the section below.

## Overview
This script creates more convenient hotkeys for switching virtual desktops in Windows 11 and solve FN left right arrows form DELL XPS 9700, 9500, 9710, 9510. Capslock is sacrificed 

## Running
[Install AutoHotkey](https://autohotkey.com/download/) v1.1 or later, then run the `desktop_switcher.ahk` script (open with AutoHotkey if prompted). You can disable the switching animation by opening "Adjust the appearance and performance of Windows" and then unselecting the checkmark "Animate windows when minimizing and maximizing".

A more detailed description of hotkeys can be found here: [AutoHotkey docs](https://autohotkey.com/docs/Hotkeys.htm).<br>

## Credits

- Thanks to [Ciantic/VirtualDesktopAccessor](https://github.com/Ciantic/VirtualDesktopAccessor) (DLL) and [sdias/win-10-virtual-desktop-enhancer](https://github.com/sdias/win-10-virtual-desktop-enhancer) (DLL usage samples), our code can now move windows between desktops.
