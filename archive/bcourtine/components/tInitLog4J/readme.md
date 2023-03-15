## <img src='./logo.jpg' width='40' height='40'>tInitLog4J

### Overview
This component is a rewriting of David Robin's InitLog4J component for Talend 3.1+ version.

This development was sponsored by French Health Ministry.

It has the following features :
- xml and properties configuration files are both supported
- a "lock configuration" checkbox allows to lock configuration (to avoid a configuration reset in a subjob, for example)
- a "die on error" checkbox allows to exit job if configuration file does not exist


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-212/screenshot.jpg)
### Images




#### Release Notes

##### 1.0 - 2009-10-28 14:53:14
Initial revision.
##### 1.1 - 2009-11-05 09:54:14
- Java 1.5 compatibility (1.0 version was only compatible with Java 1.6+)
- If "die on error", file read permission is checked (in 1.0 version, only file existence was verified)
##### 1.2 - 2010-09-13 08:33:23
Log4J library upgrade, from 1.2.15 to 1.2.16, released in april 2010.

Component required libraries are provided in the "tLog4J" component.
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)