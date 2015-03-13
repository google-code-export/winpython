## Requirements ##

As some packages were built using Microsoft Visual Studio, you may have to install one of the following redistribution packages **on Windows XP and for WinPython 2.7 only**:
  * WinPython 2.7 32bit: [Microsoft Visual C++ 2008 Redistributable Package (x86)](http://www.microsoft.com/en-us/download/details.aspx?id=29)
  * WinPython 2.7 64bit: [Microsoft Visual C++ 2008 Redistributable Package (x64)](http://www.microsoft.com/en-us/download/details.aspx?id=15336)

## Installation ##

WinPython being a portable distribution, the main installer that can be downloaded [here](https://code.google.com/p/winpython/downloads/list) only copies files to a destination directory. It may however be installed more invasively into the operating system when "registering" the distribution (see [below](https://code.google.com/p/winpython/wiki/Installation#Registration)).

## Settings ##

All installed Python packages store their settings in `[WINPYTHON_DIR]\settings` instead of user profile directory (e.g. `C:\Users\username` in Windows Vista/7/8), hence allowing to move your settings with your favorite distribution, in a portable way. This is the default behavior but it can be changed by simply removing the `[WINPYTHON_DIR]\settings` folder, forcing WinPython to use the user profile directory instead.

## Registration ##

The [WinPython Control Panel](ControlPanel.md) allows to "register" your WinPython distribution to Windows (see screenshot below).

![https://winpython.googlecode.com/files/wpcp_register_2741.png](https://winpython.googlecode.com/files/wpcp_register_2741.png)

Registering your WinPython installation will:
  * associate file extensions `.py`, `.pyc` and `.pyo` to Python interpreter
  * register Python icons in Windows explorer
  * add context menu entries `Edit with IDLE` and `Edit with Spyder` for `.py` files
  * register WinPython as a standard Python distribution (standard Python Windows installers will see WinPython in Windows registry)