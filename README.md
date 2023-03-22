# Firmata Test Program macOS

This "firmata_test" program works with boards running StandardFirmata version
2.2. If you need to quickly test your hardware, this stand-alone program can
access all pins. It runs from a single file (no installation needed), for quick
and easy testing!

This repo is meant to make it possible to compile this program on macOS. 
Other platforms should be supported, but not tested. To compile for other platforms, check out the original repo.

![](http://firmata.org/w/images/4/4d/Firmata_test_screenshot.png)

See [Downloads](https://github.com/youridijk/firmata_test/downloads) for binaries for macOS.

## Compiling MacOS

1. [Download the latest version of the wxwidgets source code](https://wxwidgets.org/downloads/) 
2. Clone/ download this repo
3. Place the folder containing this repo in the `samples` folder of the wxwidgets source code
4. Open the `Firmata Test.xcodeproj` file using XCode
5. Build the app using XCode

## Note
This project is a modified copy of the `minimal` project provided in the `samples` folder of the source code.
It could be possible that there are still some reference to it.