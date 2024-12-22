# qt-ilib

QT support for ilib. This software was originally in the ilib project itself, but moved off to make ilib a little cleaner.

## NodeunitTest

These files are shims that allow QT to run the javascript nodeunit unit tests from ilib inside of QML.

## FileReader

This is a plugin that allows QML-based program to read files from disk synchronously. Ilib needs this in order to read
the locale data files from disk.

## Compiling

First, you must have the following things installed:

    - QT 6
    - ant

Then, edit the build.properties files to point to the places where you have installed Qt.

Then, simply run `ant`. The output will be in the "output" directory.

## License

This project is shared under the [Apache2 license](./LICENSE)
and is copyright JEDLSoft, 2024.

## Release Notes

Release notes are all given in the [CHANGELOG](./CHANGELOG.md) file.

