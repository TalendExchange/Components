## <img src='./logo.jpg' width='40' height='40'>cIndexedFilesInput

### Overview
cIndexedFilesInput allows you to access to some specific lines in very big files, by a key and in a random way.

To use it :
- You have to create an index on your big files with component cIndexFile.
- You give a array name in component properties in order to read the index.
- You send a key to the component (in globalMap), and start the component with an iterate link, and you will get a flow of lines corresponding to the key, until the next key or until the end of the file.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-196/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2009-09-02 08:10:30
cIndexedFilesInput
##### 0.2 - 2009-09-02 15:46:10
Iterate link have not to be mandatory since we can start the component in other ways (with run if for example)
##### 0.3 - 2009-09-03 09:16:39
Added option to delete a key from index after having been used.
##### 0.4 - 2009-09-03 15:12:09
The component now returns NB_LINES after each execution. (NB_LINES contains 0 line if the key has not been found)
##### 0.5 - 2009-10-15 10:10:12
Performance improvement.
10% faster
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)