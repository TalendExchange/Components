## <img src='./logo.jpg' width='40' height='40'>StaticThreadLocalMap

### Overview
This component provides tools to store values in a Map.

This routines are the same as the StaticMap routines, but this Map is instanciated once by Thread.

If a Java launcher is used to execute several jobs in different Threads at the same time, using the StaticMap could result in a bug if various jobs use the same keys of the Map.

Theses routines solve this potential bug. But by definition, this routines won't allow to share information between threads.
### Images




#### Release Notes

##### 1.0 - 2010-03-15 13:22:07
Initial revision.
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)