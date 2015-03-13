## General behavior ##

The default behavior of WinPython regarding your machine configuration is to keep a low profile: no key is added to Windows registry, no shortcut is added to Windows start menu, and so on (unless you [register](https://code.google.com/p/winpython/wiki/Installation#Registration) your distribution).

Similarly, the environment variables are almost not affected by WinPython, except for the `PATH` environment variable which is modified at runtime by prepending and appending some required WinPython paths. But the original `PATH` contents are still there. This may cause conflict issues from time to time, hence the next section.

## Customizing WinPython environment variables ##

Since v2.7.5.1 and v3.3.2.1, it is possible to override any environment variable in WinPython at runtime using the new WinPython configuration file named `winpython.ini` and located in `settings` WinPython folder (or in your user profile directory if you have removed the `settings` folder).

Here is the template `winpython.ini` file which is created at runtime (if the file doesn't exist yet):

```
[debug]
state = disabled

[environment]
## <?> Uncomment lines to override environment variables
#PATH = 
#PYTHONPATH = 
#PYTHONSTARTUP = 
```

Overriding the `PATH` environment variable is quite simple:

```
[environment]
## <?> Uncomment lines to override environment variables
PATH = D:\foobar
```

That's it.