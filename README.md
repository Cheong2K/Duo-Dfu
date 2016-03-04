# Duo-Dfu GUI Frontend

=======================================

Simple GUI frontend to dfu-util

dfu-util can be found here: [dfu-util](http://dfu-util.gnumonks.org/)
Please use 0.8 or higher if possible.


Building
--------

### Linux

Requires: qt5

```make a new Qt project```

```replace the src file(main.pp/mainwindow.cpp/mainwindow.h/mainwindow.ui)```

```build the project```

### Mac

Requires: qt5


```make a new Qt project```

```replace the src file(main.pp/mainwindow.cpp/mainwindow.h/mainwindow.ui)```

```build the project```

### Windows

Requires: [Qt5](http://qt-project.org/qt5 with mingw32), [cmake 3.0+](http://www.cmake.org/download/)

The easiest way is to use QtCreator.
Open up the CMakeLists.txt file with QtCreator (make sure to select a build directory different from the source directory)
Run build



Installation
------------

copy `dfu-util.exe` to the same directory as `Duo-dfu.exe`



Usage
-----
### Windows \ OS X
Run `./Duo-dfu` or `Duo-dfu.exe`

Browse to the *.bin* file to flash.
Select the file Mode 
Click Flash


List Devices can be used to see if dfu-util can see your device.

### Linux
You may need to run the utility as root.





Spec Additions/Fixes
--------------------

Contact http://discuss.redbear.cc/ 
Or by email -> jianxing@redbear.cc