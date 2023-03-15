## <img src='./logo.jpg' width='40' height='40'>tLog4J

### Overview
This component is a rewriting of David Robin's Log4J component for Talend 3.1+ version.

This development was sponsored by French Health Ministry.

This component has the following features :
- by default, the Logger is the class logger > "Logger.getLogger(this.getClass());"
- a specific named logger can be choosen instead of the default logger
- 6 log levels : trace, debug, info, warning, error, fatal
- flow informations can be used in the log message


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-211/screenshot.jpg)
### Images




#### Release Notes

##### 1.0 - 2009-10-28 14:54:05
Initial revision.
##### 1.1 - 2009-10-30 10:11:00
Changes since 1.0 :
- data autopropagate in order to have an output component after logging data (in 1.0 version, data are not propagated).
##### 1.2 - 2010-09-13 08:36:17
Log4J library upgrade, from 1.2.15 to 1.2.16, released in april 2010.
##### 1.3 - 2010-10-26 10:33:50
New features :
- optional log message before the data loop, with a custom logging level
- optional log message after the data loop, with a custom logging level
- conditional logging : only row that verify the condition are logged.
- new variable "NB_LOGGED_LINE"
##### 1.4 - 2011-07-09 07:34:51
New features:
- component is now \\\\\\'startable\\\\\\' and can be used in a job without input flow.
- component can have an input \\\\\\'iterate\\\\\\', \\\\\\'onSubjobOk\\\\\\' or \\\\\\'onSubjobError\\\\\\' trigger
- component main log can be disabled (to keep only a begin and/or a end log)

### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)
 -   4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)