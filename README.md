[![Build Status](https://api.travis-ci.org/unified-font-object/ufoLib.svg)](https://travis-ci.org/unified-font-object/ufoLib)
[![AppVeyor Status](https://ci.appveyor.com/api/projects/status/github/unified-font-object/ufoLib?svg=true)](https://ci.appveyor.com/project/adrientetar/ufolib)
![Python Versions](https://img.shields.io/badge/python-2.7%2C%203.5%2C%203.6-blue.svg)
[![PyPI](https://img.shields.io/pypi/v/ufoLib.svg)](https://pypi.org/project/ufoLib/)
[![codecov](https://codecov.io/gh/unified-font-object/ufoLib/branch/master/graph/badge.svg)](https://codecov.io/gh/unified-font-object/ufoLib)

ufoLib
------

⚠️ **ufoLib moved to [fontTools.ufoLib]** 

A low-level [UFO] reader and writer.

[UFO] is a human-readable, XML-based file format that stores font source files.

### Installation

```sh
$ pip install ufoLib
```

For better speed, you can install with extra dependencies like this:

```sh
$ pip install ufoLib[lxml]
```

[UFO]: http://unifiedfontobject.org/
[fontTools.ufoLib]: http://github.com/fonttools/fonttools/tree/master/Lib/fontTools/ufoLib