Programmiersprachen: helloworld
===========

[![Build Linux](https://github.com/vrsys/programmiersprachen-helloworld/actions/workflows/build-linux.yml/badge.svg)](https://github.com/vrsys/programmiersprachen-helloworld/actions/workflows/build-linux.yml)
[![Build macOS](https://github.com/vrsys/programmiersprachen-helloworld/actions/workflows/build-macos.yml/badge.svg)](https://github.com/vrsys/programmiersprachen-helloworld/actions/workflows/build-macos.yml)
[![Build Windows](https://github.com/vrsys/programmiersprachen-helloworld/actions/workflows/build-windows.yml/badge.svg)](https://github.com/vrsys/programmiersprachen-helloworld/actions/workflows/build-windows.yml)
[![Doctest](https://github.com/vrsys/programmiersprachen-helloworld/actions/workflows/doctest.yml/badge.svg)](https://github.com/vrsys/programmiersprachen-helloworld/actions/workflows/doctest.yml)

Repository template for **Assignment 1** of the Programming Languages course (*Programmiersprachen*).
This assignment introduces the basics of C++, including setting up a build environment with CMake, writing and compiling simple programs, using git for version control, and running first unit tests with [doctest](https://github.com/doctest/doctest).

## Build

```bash
mkdir build
cd build
cmake ..
make

# run the apps
cd source
./helloworld
./tests
```
