
VocalTractLab
=============

This is an __unofficial__ [VocalTractLab] repository, for building on Linux+GNU.

[VocalTractLab]: https://www.vocaltractlab.de/

The __official__ repositories are [VocalTractLab GUI] and [VocalTractLab Backend].

[VocalTractLab GUI]: https://github.com/TUD-STKS/VocalTractLab-dev
[VocalTractLab Backend]: https://github.com/TUD-STKS/VocalTractLabBackend-dev

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
cmake --build .
```

If CMake can't find wxWidgets, set the environment variable WX_CONFIG with
the path to the program `wx-config`, for example:

```
WX_CONFIG=/usr/local/bin/wx-config cmake -D CMAKE_BUILD_TYPE=Release ..
```
