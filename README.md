# BLE_Scanner32x
How it works:

This is a Simple BLE Scanner that prints out all the advertisers around it.

Tools and SDKs:

This was tested with:

Silicon Labs Bluetooth Stack 3.2.1.0


GNU GCC Compiler: Apple LLVM version 9.0.0 (clang-900.0.39.2) Target: x86_64-apple-darwin16.7.0 Thread model: posix

Development Board: Silicon Labs WSTK with BRD4181A/B

Usage:

In order to avoid modifying the Make File, please clone this to the following folder on the Bluetooth SDK structure.

/Applications/SimplicityStudio5.app/Contents/Eclipse/developer/sdks/gecko_sdk_suite/v3.2/app/bluetooth/example_host/BLE_Scanner32x

It should compile as is.

In order to execute it, please use the following command:

./exe/BLE_Scanner -u /dev/tty.usbmodem0004400337201 115200 1

If you desire to use this with a different Host, you will need to modify the Makefile in order to accommodate the cross compiler.
