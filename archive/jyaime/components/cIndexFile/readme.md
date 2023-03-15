## <img src='./logo.jpg' width='40' height='40'>cIndexFile

### Overview
cIndexFile allows you to index very big files in order to access them after, in a random way.
The purpose of this component is to access to pieces of data in very very big files. (which can't be mounted in memory)

To use it :
- You give a regexp expression with a "group" used to match a key (ie "^PIECESTART(....KEY.....)0100.*" indexed key is between () )
- You give a array name in component properties in order to store index 
- You can use several components cIndexFile to index multiple files, and store indexes in a common array.

Then with component cIndexedFilesInput, you just have to ask for a "key", and it will give you the part corresponding to this key in the file.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-195/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2009-09-02 08:11:07
cIndexFile
##### 0.2 - 2009-09-11 09:47:33
Icon updated (not an input flow).
### Compatible
 -  3.1 (obsolete)