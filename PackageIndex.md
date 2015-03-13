## WinPython 2 or WinPython 3 ##

**Two major versions** of the Python programming language are currently maintained: [Python 2 and Python 3](http://wiki.python.org/moin/Python2orPython3). In 2012, Python 2 is still the most used version for scientific applications even a vast majority of commonly used scientific Python libraries are already available for Python 3.

As a consequence, there are two major versions of WinPython: WinPython 2 and WinPython 3, respectively based on Python 2 and Python 3. Package index may vary depending on each package Python 3 migration status.


---


## Python 3 specific issues ##

### Blocking packages ###

None.

All those (previously blocking) packages have been ported to Python 3.3+:
  * Packages which have required a lot of work to be made compatible with Python 3:
    * [guidata](http://packages.python.org/guidata) (done since [this revision](http://code.google.com/p/guidata/source/detail?r=f2fa6a04311915e743f2d108f70961fa9ee53755))
    * [guiqwt](http://packages.python.org/guiqwt) (no longer blocked by PyQwt... see [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyqwt), done since [this revision](http://code.google.com/p/guiqwt/source/detail?r=876549c2468c37550de6e23b9546074a8e22e61d))
    * [spyder](http://pypi.python.org/pypi/spyder) (experimental since [this revision](http://code.google.com/p/spyderlib/source/detail?r=44c866be17926867c7018e5f40888f8b167a9773&repo=v21))
  * Packages which have required less coding effort:
    * [formlayout](http://formlayout.googlecode.com) (done)
    * [winpython](http://code.google.com/p/winpython) (done)

### Optional packages ###

The following packages will be part of this version of WinPython as soon as they will be available for Python 3.3 but they are not considered as essential:
  * Packages which are not yet available for Python 3:
    * [mxBase](http://www.egenix.com/products/python/mxBase)
    * [PyWavelets](http://www.pybytes.com/pywavelets)
    * [reportlab](http://www.reportlab.org)
    * [ViTables](http://vitables.org)
    * [VTK](http://www.vtk.org)