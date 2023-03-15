## <img src='./logo.jpg' width='40' height='40'>tBufferCopyInput

### Overview
With original Talend tBufferInput component, it is not possible to make in the same subjob a chain "tBufferInput > ... > tBufferOutput", since these two components use the same globalBuffer list.

This tBufferCopyInput makes a copy of the globalBuffer list, and reads data rows from this copy. After that, the tBufferOutput can write data rows in the global buffer without memory exception.

So a chain "tBufferCopyInput > ... > tBufferOutput" works fine.

After making a copy of the global buffer, it is possible to clear it, in order to allow the tBufferOutput component to write data rows in an empty buffer.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-154/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2009-05-08 07:22:13
Initial revision
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)