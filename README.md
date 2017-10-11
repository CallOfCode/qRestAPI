# OVERVIEW

qRestAPI is a cross-platform Qt-based library allowing to easily query REST endpoints.

For convenience, it also provides specialized interface to query [Midas](http://midasplatform.org/) servers.

## Prerequisites

 * Qt 4 or Qt 5
 * [CMake](http://www.cmake.org) >= 3.5.0

## How to build against Qt4

    git clone git://github.com/commontk/qRestAPI.git
    mkdir qRestAPI-build
    cd qRestAPI-build
    cmake -DQT_QMAKE_EXECUTABLE:FILEPATH=/path/to/cmake ../qRestAPI
    make -j4
    ctest

## How to build against Qt5

    git clone git://github.com/commontk/qRestAPI.git
    mkdir qRestAPI-build
    cd qRestAPI-build
    cmake -DQ5_DIR:PATH=/path/to/Qt5.9.1/5.9.1/gcc_64/lib/cmake/Qt5 ../qRestAPI
    make -j4
    ctest

## Contribute

Contributions are welcome, and they are greatly appreciated! Every little bit helps, and credit will always be given.

See [CONTRIBUTING.md][contributing] for more details.

[contributing]: https://github.com/commontk/qRestAPI/blob/master/CONTRIBUTING.md
