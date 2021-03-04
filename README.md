**makedeb** - is a wizard for building simple DEB packages from pre-installed files (scripts, etc.)

Dependencies: `zenity, dpkg-dev`

Sometimes there is a need to issue a certain bunch of scripts (files) in the form of a `*.deb` package. Building a package consists of two steps: selecting the necessary files (finish selection = `Cancel` button) and entering the required parameters (see the screenshot).

If the package is re-created and only the contents of the files themselves that are collected in the `*.deb` package are changed, you can issue the command: `makedeb make` to skip the previous steps of entering the information already entered earlier and perform only the final reassembly of the package. The finished `*.deb` package is created in the `~/makedeb` folder. The startup shortcut is located in `Utilities-System`.

Made and tested in Mageia Linux-8.
