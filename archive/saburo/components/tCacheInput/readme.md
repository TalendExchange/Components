## <img src='./logo.jpg' width='40' height='40'>tCacheInput

### Overview
Reads data cached using a tCacheOutput component.

It can read a memory buffer or a cache file.
### Images




#### Release Notes

##### 0.2 - 2011-05-12 05:57:16
First public release of the tCacheInput component
##### 0.3 - 2011-06-08 16:40:54
Improved memory management (better cleanup if the "remove buffer after read" option is checked)
##### 0.4 - 2012-01-31 16:54:16
the global buffer name variable is now dynamic, meaning you can set it like : \\"buffer_\\"+context.bufname\\". 

For this reason , when using a constant string, it NOW has to be enclosed in \\"\\"

Update accordingly your existing jobs if you used this option

### Compatible
 -  4.0 (obsolete)
 -   4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)