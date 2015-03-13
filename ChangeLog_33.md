## History of changes for WinPython 3.3.2.3 ##

The following changes were made to WinPython distribution since version 3.3.2.2.

### Python packages ###

New packages:

  * [logilab-astng](http://pypi.python.org/pypi/logilab-astng) 0.24.3 (Rebuild a new abstract syntax tree from Python's ast (required for pylint))
  * [logilab-common](http://pypi.python.org/pypi/logilab-common) 0.60.0 (Collection of low-level Python packages and modules used by Logilab projects (required for pylint))
  * [patsy](http://pypi.python.org/pypi/patsy) 0.2.0 (Describing statistical models using symbolic formulas)
  * [pylint](http://www.logilab.org/project/pylint) 0.28.0 (Logilab code analysis module: analyzes Python source code looking for bugs and signs of poor quality)

Upgraded packages:

  * [PySide](https://pypi.python.org/pypi/PySide) 1.2.0 → 1.2.1 (Python binding of the cross-platform GUI toolkit Qt)
  * [setuptools](http://pypi.python.org/pypi/setuptools) 0.9.8 → 1.0 (Download, build, install, upgrade, and uninstall Python packages - easily)
  * [spyder](http://pypi.python.org/pypi/spyder) 2.3.0dev5 → 2.3.0dev6 (Scientific PYthon Development EnviRonment: designed for interactive computing and data visualisation with a simple and intuitive user interface)
  * [winpython](http://code.google.com/p/winpython) 0.16 → 0.17 (WinPython distribution tools, including WPPM (package manager))


---


## History of changes for WinPython 3.3.2.2 ##

The following changes were made to WinPython distribution since version 3.3.2.0.

### Python packages ###

New packages:

  * [MarkupSafe](http://pypi.python.org/pypi/MarkupSafe) 0.18 (Implements a XML/HTML/XHTML Markup safe string for Python)
  * [pyparsing](http://pyparsing.wikispaces.com/) 2.0.1 (A Python Parsing Module)
  * [pyserial](http://sourceforge.net/projects/pyserial) 2.6 (Library encapsulating the access for the serial port)
  * [python-dateutil](http://labix.org/python-dateutil) 2.1 (Powerful extensions to the standard datetime module)
  * [pytz](http://pytz.sourceforge.net/) 2013b (World Timezone Definitions for Python)
  * [setuptools](http://pypi.python.org/pypi/setuptools) 0.9.8 (Download, build, install, upgrade, and uninstall Python packages - easily)
  * [six](http://pypi.python.org/pypi/six) 1.3.0 (Python 2 and 3 compatibility utilities)
  * [statsmodels](http://pypi.python.org/pypi/statsmodels) 0.5.0 (Statistical computations and models for use with SciPy)

Upgraded packages:

  * [Jinja2](http://jinja.pocoo.org) 2.7 → 2.7.1 (Sandboxed template engine (provides a Django-like non-XML syntax and compiles templates into executable python code))
  * [Pillow](http://pypi.python.org/pypi/Pillow) 2.0.0 → 2.1.0 (Python Imaging Library (fork))
  * [PySide](https://pypi.python.org/pypi/PySide) 1.1.2 → 1.2.0 (Python binding of the cross-platform GUI toolkit Qt)
  * [Scidoc](http://pypi.python.org/pypi/Scidoc) 1.7.1 → 1.7.1.1 (Scidoc installs scientific libraries documentation (NumPy, SciPy, ...))
  * [docutils](http://docutils.sourceforge.net) 0.10 → 0.11 (Text processing system for processing plaintext documentation into useful formats, such as HTML or LaTeX (includes reStructuredText))
  * [guiqwt](http://packages.python.org/guiqwt) 2.3.0 → 2.3.1 (Efficient curve/image plotting and other GUI tools for scientific data processing software development)
  * [ipython](http://ipython.org) 0.13.2 → 1.0.0 (Enhanced Python shell)
  * [mahotas](http://pypi.python.org/pypi/mahotas) 1.0 → 1.0.2 (Computer Vision library)
  * [matplotlib](http://matplotlib.sourceforge.net) 1.2.1 → 1.3.0 (2D plotting library (embeddable in GUIs created with PyQt))
  * [networkx](http://pypi.python.org/pypi/networkx) 1.7 → 1.8.1 (Python package for creating and manipulating graphs and networks)
  * [pandas](http://pypi.python.org/pypi/pandas) 0.11.0 → 0.12.0 (Powerful data structures for data analysis, time series and statistics)
  * [pip](http://pypi.python.org/pypi/pip) 1.3.1 → 1.4.1 (A tool for installing and managing Python packages)
  * [psutil](http://code.google.com/p/psutil) 0.7.1 → 1.0.1 (Provides an interface for retrieving information on all running processes and system utilization (CPU, disk, memory, network) in a portable way)
  * [pywin32](http://sourceforge.net/projects/pywin32) 218 → 218.4 (Python library for Windows)
  * [scikit-learn](http://pypi.python.org/pypi/scikit-learn) 0.13.1 → 0.14.1 (A set of Python modules for machine learning and data mining)
  * [spyder](http://pypi.python.org/pypi/spyder) 2.3.0dev1 → 2.3.0dev5 (Scientific PYthon Development EnviRonment: designed for interactive computing and data visualisation with a simple and intuitive user interface)
  * [sympy](http://code.google.com/p/sympy) 0.7.2 → 0.7.3 (Symbolic Mathematics Library)
  * [tables](http://www.pytables.org) 3.0.0rc2 → 3.0.0 (Package based on HDF5 library for managing hierarchical datasets (extremely large amounts of data))
  * [winpython](http://code.google.com/p/winpython) 0.14 → 0.16 (WinPython distribution tools, including WPPM (package manager))

Removed packages:

  * [distribute](http://pypi.python.org/pypi/distribute) 0.6.40 (Download, build, install, upgrade, and uninstall Python packages - easily)


---


## History of changes for WinPython 3.3.2.1 ##

The following changes were made to WinPython distribution since version 3.3.2.0.

### Internals ###

Added support for Environment Variables customization using the new `settings\winpython.ini` configuration file (see [here](Environment.md) for more details).

### Python packages ###

New packages:

  * [MarkupSafe](http://pypi.python.org/pypi/MarkupSafe) 0.18 (Implements a XML/HTML/XHTML Markup safe string for Python)
  * [statsmodels](http://pypi.python.org/pypi/statsmodels) 0.4.3 (Statistical computations and models for use with SciPy)

Upgraded packages:

  * [distribute](http://pypi.python.org/pypi/distribute) 0.6.40 → 0.6.43 (Download, build, install, upgrade, and uninstall Python packages - easily)
  * [spyder](http://pypi.python.org/pypi/spyder) 2.3.0dev1 → 2.3.0dev3 (Scientific PYthon Development EnviRonment: designed for interactive computing and data visualisation with a simple and intuitive user interface)
  * [tables](http://www.pytables.org) 3.0.0rc2 → 3.0.0rc3 (Package based on HDF5 library for managing hierarchical datasets (extremely large amounts of data))
  * [winpython](http://code.google.com/p/winpython) 0.14 → 0.15 (WinPython distribution tools, including WPPM (package manager))


---


## History of changes for WinPython 3.3.2.0 ##

The following changes were made to WinPython distribution since version 3.3.1.1.

### Tools ###

Upgraded packages:

  * [TortoiseHg](http://tortoisehg.bitbucket.org) 2.7.2 → 2.8 (Set of graphical tools and a shell extension for the Mercurial distributed revision control system)

### Python packages ###

New packages:

  * [colorama](http://pypi.python.org/pypi/colorama) 0.2.5 (Cross-platform colored terminal text)

Upgraded packages:

  * [Cython](http://www.cython.org) 0.19 → 0.19.1 (Cython is a language that makes writing C extensions for the Python language as easy as Python)
  * [Jinja2](http://jinja.pocoo.org) 2.6 → 2.7 (Sandboxed template engine (provides a Django-like non-XML syntax and compiles templates into executable python code))
  * [Python](http://www.python.org/) 3.3.1 → 3.3.2 (Python programming language with standard library)
  * [cvxopt](http://abel.ee.ucla.edu/cvxopt) 1.1.5 → 1.1.6 (Convex optimization library)
  * [distribute](http://pypi.python.org/pypi/distribute) 0.6.38 → 0.6.40 (Download, build, install, upgrade, and uninstall Python packages - easily)
  * [guidata](http://packages.python.org/guidata) 1.6.0dev2 → 1.6.1 (Automatically generated graphical user interfaces for easy data set edition and display)
  * [guiqwt](http://packages.python.org/guiqwt) 2.3.0dev2 → 2.3.0 (Efficient curve/image plotting and other GUI tools for scientific data processing software development)
  * [mahotas](http://pypi.python.org/pypi/mahotas) 0.99 → 1.0 (Computer Vision library)
  * [scikit-image](http://pypi.python.org/pypi/scikit-image) 0.8.1 → 0.8.2 (Image processing toolbox for SciPy)
  * [simplejson](http://pypi.python.org/pypi/simplejson) 3.2.0 → 3.3.0 (Simple, fast, extensible JSON (JavaScript Object Notation) encoder/decoder)
  * [spyder](http://pypi.python.org/pypi/spyder) 2.1.14dev4 → 2.3.0dev1 (Scientific PYthon Development EnviRonment: designed for interactive computing and data visualisation with a simple and intuitive user interface)
  * [tables](http://www.pytables.org) 3.0.0b1 → 3.0.0rc2 (Package based on HDF5 library for managing hierarchical datasets (extremely large amounts of data))
  * [winpython](http://code.google.com/p/winpython) 0.13 → 0.14 (WinPython distribution tools, including WPPM (package manager))


---


## History of changes for WinPython 3.3.1.1 ##

The following changes were made to WinPython distribution since version 3.3.1.0.

### Internals ###

The following changes were made to WinPython tools (`winpython` Python package), including WPPM, WPCP and the distribution generation script (`make.py` and its dependencies):
  * WinPython Control Panel: added shortcut to command prompt
  * Bugfix: all launchers now accept command line options -- Example, for executing IPython Qt console without pylab mode enabled, just create a shortcut pointing to "IPython Qt console.exe" and add the option "--pylab=None"
  * Added launcher for IPython notebook
  * WinPython registration: now registers entries in HKCU\Software\Python\PythonCore. In other words, any distutils Python package will see WinPython distribution as a standard installed Python distribution

### Python packages ###

Upgraded packages:

  * [formlayout](http://formlayout.googlecode.com) 1.0.12 → 1.0.13 (Module for creating form dialogs/widgets to edit various type of parameters without having to write any GUI code)
  * [distribute](http://pypi.python.org/pypi/distribute) 0.6.36 → 0.6.38 (Download, build, install, upgrade, and uninstall Python packages - easily)
  * [simplejson](http://pypi.python.org/pypi/simplejson) 3.1.3 → 3.2.0 (Simple, fast, extensible JSON (JavaScript Object Notation) encoder/decoder)
  * [mahotas](http://pypi.python.org/pypi/mahotas) 0.9.8 → 0.99 (Computer Vision library)
  * [psutil](http://code.google.com/p/psutil) 0.7.0 → 0.7.1 (Provides an interface for retrieving information on all running processes and system utilization (CPU, disk, memory, network) in a portable way)
  * [winpython](http://code.google.com/p/winpython) 0.12 → 0.13 (WinPython distribution tools, including WPPM (package manager))


---


## History of changes for WinPython 3.3.1.0 ##

The following changes were made to WinPython distribution since version 3.3.0.0beta2.

### Internals ###

The following changes were made to WinPython tools (`winpython` Python package), including WPPM, WPCP and the distribution generation script (`make.py` and its dependencies):
  * utils: added `set_env` and `get_env` functions (will be useful to fix [Issue 35](https://code.google.com/p/winpython/issues/detail?id=35))
  * Register WinPython distribution:
    * Added "Edit with Spyder" to context menu entries (requires Spyder 2.2+)
    * Added "unregistration" process (WinPython Control Panel: new "Unregister distribution..." entry in "Advanced" menu)
  * [Issue 19](https://code.google.com/p/winpython/issues/detail?id=19): Disable 'settings' folder (%HOME% redirection) by renaming/deleting the directory
  * WinPython control panel ([Issue 29](https://code.google.com/p/winpython/issues/detail?id=29)): removed embedded Python (Spyder) console
  * Batch scripts: removed unnecessary "cd %WINPYDIR%" (this became unnecessary)
  * Fixed 'register\_python.bat' scripts following changes in command line options (these changes were made in revision 9a62581ae693)
  * py3compat: fixed ImportError on non Windows plaforms due to winreg/_winreg_

### Tools ###

Upgraded packages:

  * [TortoiseHg](http://tortoisehg.bitbucket.org) 2.6 → 2.7.2 (Set of graphical tools and a shell extension for the Mercurial distributed revision control system)

### Python packages ###

New packages:

  * [tables](http://www.pytables.org) 3.0.0b1 (Package based on HDF5 library for managing hierarchical datasets (extremely large amounts of data))
  * [cvxopt](http://abel.ee.ucla.edu/cvxopt) 1.1.5 (Convex optimization library)
  * [simplejson](http://pypi.python.org/pypi/simplejson) 3.1.3 (Simple, fast, extensible JSON (JavaScript Object Notation) encoder/decoder)
  * [PySide](https://pypi.python.org/pypi/PySide) 1.1.2 (Python binding of the cross-platform GUI toolkit Qt)
  * [Pillow](http://pypi.python.org/pypi/Pillow) 2.0.0 (Python Imaging Library (fork))
  * [pip](http://pypi.python.org/pypi/pip) 1.3.1 (A tool for installing and managing Python packages)
  * [pyreadline](http://ipython.org/pyreadline.html) 2.0 (IPython needs this module to display color text in Windows command window)
  * [networkx](http://pypi.python.org/pypi/networkx) 1.7 (Python package for creating and manipulating graphs and networks)
  * [mahotas](http://pypi.python.org/pypi/mahotas) 0.9.8 (Computer Vision library)
  * [numexpr](http://code.google.com/p/numexpr) 2.1 (Fast evaluation of array expressions elementwise by using a vector-based virtual machine)
  * [VPython](http://www.vpython.org) 5.74 (A free, open-source module for producing real-time 3D scenes with Python)
  * [xlrd](http://pypi.python.org/pypi/xlrd) 0.9.2 (Extract data from Microsoft Excel spreadsheet files)

Upgraded packages:

  * [Cython](http://www.cython.org) 0.17.4 → 0.19 (Cython is a language that makes writing C extensions for the Python language as easy as Python)
  * [distribute](http://pypi.python.org/pypi/distribute) 0.6.33 → 0.6.36 (Download, build, install, upgrade, and uninstall Python packages - easily)
  * [Python](http://www.python.org/) 3.3.0 → 3.3.1 (Python programming language with standard library)
  * [Scidoc](http://pypi.python.org/pypi/Scidoc) 1.6.2.1 → 1.7.1 (Scidoc installs scientific libraries documentation (NumPy, SciPy, ...))
  * [pandas](http://pypi.python.org/pypi/pandas) 0.10.1 → 0.11.0 (Powerful data structures for data analysis, time series and statistics)
  * [pyzmq](http://pypi.python.org/pypi/pyzmq) 2.2.0.1 → 13.1.0 (Lightweight and super-fast messaging based on ZeroMQ library (required for IPython Qt console))
  * [numpy-MKL](http://numpy.scipy.org/) 1.7.0rc1 → 1.7.1 (NumPy: multidimensional array processing for numbers, strings, records and objects (SciPy's core module))
  * [scikit-image](http://pypi.python.org/pypi/scikit-image) 0.7.2 → 0.8.1 (Image processing toolbox for SciPy)
  * [matplotlib](http://matplotlib.sourceforge.net) 1.2.0 → 1.2.1 (2D plotting library (embeddable in GUIs created with PyQt))
  * [scipy](http://www.scipy.org) 0.12.0.dev → 0.12.0 (SciPy: Scientific Library for Python (advanced math, signal processing, optimization, statistics, ...))
  * [ipython](http://ipython.org) 0.13.1 → 0.13.2 (Enhanced Python shell)
  * [scikit-learn](http://pypi.python.org/pypi/scikit-learn) 0.13 → 0.13.1 (A set of Python modules for machine learning and data mining)
  * [psutil](http://code.google.com/p/psutil) 0.6.1 → 0.7.0 (Provides an interface for retrieving information on all running processes and system utilization (CPU, disk, memory, network) in a portable way)
  * [Pygments](http://pygments.org) 1.5 → 1.6 (Generic syntax highlighter for general use in all kinds of software)
  * [winpython](http://code.google.com/p/winpython) 0.10 → 0.12 (WinPython distribution tools, including WPPM (package manager))
  * [nose](http://somethingaboutorange.com/mrl/projects/nose) 1.2.1 → 1.3.0 (nose is a discovery-based unittest extension (e.g. NumPy test module is using nose))
  * [h5py](http://code.google.com/p/h5py/) 2.1.1 → 2.1.3 (General-purpose Python interface to HDF5 files (unlike PyTables, h5py provides direct access to the full HDF5 C library))
  * [spyder](http://pypi.python.org/pypi/spyder) 2.1.14dev3 → 2.1.14dev4 (Scientific PYthon Development EnviRonment: designed for interactive computing and data visualisation with a simple and intuitive user interface)

Removed packages:

  * [PIL](http://www.pythonware.com/products/pil) 1.1.7 (Python Imaging Library - (basic) Image processing library)


---


## History of changes for WinPython 3.3.0.0beta2 ##

The following changes were made to WinPython distribution since version 3.3.0.0beta1.

### Python packages ###

New packages:

  * [scikit-learn](http://pypi.python.org/pypi/scikit-learn) 0.13 (A set of Python modules for machine learning and data mining)

Upgraded packages:

  * [pandas](http://pypi.python.org/pypi/pandas) 0.10.0 → 0.10.1 (Powerful data structures for data analysis, time series and statistics)
  * [spyder](http://pypi.python.org/pypi/spyder) 2.1.14dev2 → 2.1.14dev3 (Scientific PYthon Development EnviRonment: designed for interactive computing and data visualisation with a simple and intuitive user interface)