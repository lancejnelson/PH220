---
title:  Installing Python
sidebar: mydoc_sidebar
layout: default
permalink: installingPython.html
---


## Windows 

The easiest way to get started using Python is to download the
[Enthought Canopy Package][enthought].  (Choose version 3.??)

After the download completes, run the installer.  You should notice
that a new application appears by the name of "Enthought Canopy".
Refer to [my python book][pbook] to get started using python.

[enthought]: https://assets.enthought.com/downloads/
[pbook]: https://byuiphysics.github.io/pythonbook

## Mac

While you _can_ use the [Enthought Canopy Package][enthought] on a Mac, my personal preference when I code is to work at the command line. (If you don't know what that means, we should talk one-on-one)

Mac OS X comes with Python 2.7 out of the box.  However, I recommend that you use version 3 of python.  To verify that python is already installed, open a Terminal window and type 

```bash
python --version
```

If python is installed, you should see what version it is.  You can also try:

```bash
python3 --version
```

to see if python version 3 is installed.

We'll use an application called brew for the installation.  To install brew, open a Terminal window and type:

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Once that is finished, you can use brew to install python like this:

```bash
brew install python3
```



## Installing Libraries

Python comes packaged with something called PIP (recursive acronym:
"pip installs packages") that is a great tool for managing python
libraries.  It automatically handles all of the dependies associated
with library installs (i.e. I want to install library A, but oh wait
library A needs libraries B and C to work) and is a must for any
python user.  You can use pip to install a python library like this:

```bash
pip install matplotlib
```

You can uninstall a package like this:

```bash
pip uninstall matplotlib
```
