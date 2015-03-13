## Key features ##

WinPython is a portable distribution of Python. In other words, even if it provides a working Python environment, WinPython does **not** install Python on your machine. As a consequence, it's not possible to install packages using standard Python installers (these installers will look for Python in Windows registry and won't find it).

That's why I wrote the WinPython Package Manager (WPPM), a Python program handling package managing tasks (install, uninstall or upgrade packages) for a portable Python distribution.

WPPM currently supports the following Python package formats:

  * Standard executable installers: [distutils wininst](http://docs.python.org/distutils/builtdist.html#creating-windows-installers) (installer filename has the form: `foo-1.0.win32-py2.7.exe`)
  * Standard source distributions<sup>[1]</sup>: [distutils sdist](http://docs.python.org/distutils/sourcedist.html) (archive filename has the form: `foo-1.0.tar.gz`) -- but **only for pure-Python packages**

<sup>[1]</sup> This feature was implemented in WPPM v0.2dev included in WinPython v2.7.3.0beta3

## Get Python packages ##

The main website for finding and downloading Python packages is obviously [PyPI](http://pypi.python.org/pypi), the Python Package Index.

Please note that Christoph Gohlke's [Unofficial Windows Binaries for Python Extension Packages](http://www.lfd.uci.edu/~gohlke/pythonlibs/) provides tons of ready-to-install distutils packages.

## WPPM GUI frontend ##

WPPM has a GUI frontend which is known as the [WinPython Control Panel](ControlPanel.md).