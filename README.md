Cross Platform Desktop Application Skeleton (Qt5)
=================================================

[![Build Status](https://travis-ci.org/jonasschnelli/crossplatformskeleton.svg?branch=master)](https://travis-ci.org/jonasschnelli/crossplatformskeleton)


Building cross platform desktop applications is not a simple task.
The trend seems to use frameworks that build on top of an built in webbrowser leading to wasting tons of RAM.

This little project skeleton may help to create a simple QT based cross platform application.

Features
--------
* Supports Linux, Windows and macOS
* Cross compile system (see /depends) to compile static binaries for macOX, Windows on Linux
* Deterministic builds with gitian
* Internal C++ JSON parser (libunivalue)