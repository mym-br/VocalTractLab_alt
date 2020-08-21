
VocalTractLab
=============

This is an __unofficial__ [VocalTractLab] repository, for building on Linux+GNU.

[VocalTractLab]: https://www.vocaltractlab.de/

Requirements
------------

- A C++11 compiler.
- CMake
- pkg-config
- wxWidgets 3.1.x.
- OpenAL.
- GLU
- OpenGL

Building
--------

```
mkdir build
cd build
cmake -D CMAKE_BUILD_TYPE=Release ..
make
```

If CMake can't find wxWidgets, set the environment variable WX_CONFIG with
the path to the program `wx-config`, for example:

```
WX_CONFIG=/usr/local/bin/wx-config cmake -D CMAKE_BUILD_TYPE=Release ..
```
