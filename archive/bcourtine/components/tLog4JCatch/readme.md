## <img src='./logo.jpg' width='40' height='40'>tLog4JCatch

### Overview
Log4J interceptor for Talend native logs.

This component is a variation of tLog4J, with theses differences :
- the schema is the same as the "tLogCatcher" component and is not editable
- the log level is dynamic, based on the "priority" of Talend log message

Talend native logs will be sent to Log4J with their original log level.

Use case : a log can be sent to Log4J by Talend using the native "tWarn" component.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-213/screenshot.jpg)
### Images




#### Release Notes

##### 1.0 - 2009-10-28 14:54:49
Initial revision.
##### 1.1 - 2009-10-30 10:15:36
Changes since 1.0 :
- data autopropagate in order to have an output component after logging data (in 1.0 version, data are not propagated). 
##### 1.2 - 2010-09-13 08:37:46
Log4J library upgrade, from 1.2.15 to 1.2.16, released in april 2010.

Required libraries are provided in the "tLog4J" component.
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)