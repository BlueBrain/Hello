# Hello

Welcome to Hello, a C++ library to rule the world.

## Features

Hello provides the following functionality:
* Rule the world
* Provide a C++/CMake template for the Blue Brain Project
* [Documentation](http://bluebrain.github.io/Hello-1.0/documentation.html)

## Building from Source

Hello is a cross-platform library, designed to run on any modern
operating system, including all Unix variants and the Windows operating
system. It requires a C++11 compiler and uses CMake to create a
platform-specific build environment. The following platforms and build
environments are tested:

* Linux: Ubuntu 16.04, RHEL 6.8 (Makefile, Ninja)
* Windows: 7 (Visual Studio 2012)
* Mac OS X: 10.9 (Makefile, Ninja)

Building from source is as simple as:

    git clone --recursive https://github.com/BlueBrain/Hello.git
    mkdir Hello/build
    cd Hello/build
    cmake -GNinja ..
    ninja

## Funding & Acknowledgment
 
The development of this software was supported by funding to the Blue Brain Project,
a research center of the École polytechnique fédérale de Lausanne (EPFL), from the
Swiss government’s ETH Board of the Swiss Federal Institutes of Technology.
 
Copyright (C) 2013-2021 Blue Brain Project/EPFL
