# Color Database
This repository contains a Python 2.7 module that defines a ColorDB class and several utility functions.

Usage
To use the ColorDB class, you must first instantiate it by calling the `get_colordb()` function, passing it the name of a file containing a color database. The get_colordb() function will try to determine the format of the file, and will return an instance of the ColorDB class.

python
Copy code
```from colordb import get_colordb```

```db = get_colordb('rgb.txt')```
The `get_colordb()` function can also take an optional argument specifying the format of the file, if it cannot determine the format automatically.

python
Copy code
```db = get_colordb('colors.txt', filetype='X_RGB_TXT')```
Color formats
The ColorDB class supports color values in the RGB color space, with intensities ranging from 0 to 255 for each of the red, green, and blue channels.

The class provides several utility functions for converting between different color formats, and for calculating other color values.

Authorship
This module was originally written by Jim Fulton.

This repository contains a Python 3.0+ adaptation of the module, which was translated by Eric Pan.

You can support TriangleLabs, Eric Pan's development lab, by visiting his Patreon page at https://patreon.com/TriangleLabs.
