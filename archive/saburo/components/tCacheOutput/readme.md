## <img src='./logo.jpg' width='40' height='40'>tCacheOutput

### Overview
Stores data in a memory buffer and / or to disk. Buffers can be loaded incrementally using iterations.

Memorized data can then be consumed using a tCacheInput component.
The current release does not use data compression.

### Images




#### Release Notes

##### 0.2 - 2011-05-12 05:54:37
First public release of the tCacheOutput component
##### 0.4 - 2012-01-31 16:55:33
the global buffer name variable is now dynamic, meaning you can set it like : \\"buffer_\\"+context.bufname\\". 

For this reason , when using a constant string, it NOW has to be enclosed in \\"\\"

Update accordingly your existing jobs if you used this option
### Compatible
 -  4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)