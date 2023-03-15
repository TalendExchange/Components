## <img src='./logo.jpg' width='40' height='40'>tSerialInput

### Overview
tSerialInput reads data from the serial port and it produces an output data flow with a single tString field, containing the line received.

Lines are terminated by a configurable terminator (default is \
 ).

It is based on the gnu.io RXTX library which has to be installed separately as it requires a different jar depending on your operating system (to access the hardware, such as comports, java needs JNI, which is specific for each architecture) 


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-455/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2012-01-05 18:57:31
First release of the component, can read data from the serail port, no writing functionality is currently implemented (but planned for future releases, for protocol management)
### Compatible
 -  5.0 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)