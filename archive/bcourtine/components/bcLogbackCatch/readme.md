## <img src='./logo.jpg' width='40' height='40'>bcLogbackCatch

### Overview
Redirect the Talend logs (from "tLogCatcher" component) to the Logback logging Framework, with the original log level.

Since fatal log level is not supported by Logback, fatal logs are converted into error logs.

Component required libraries are provided in the "bclogback" component.

Note: this component uses the SLF4J API, and no Logback class are direcly used. So, the component can be used with every other logging Framework supported by SLF4J: you just need to replace Logback jar files in the job classpath.
### Images




#### Release Notes

##### 1.1 - 2010-09-13 08:22:00
First release.
##### 1.2 - 2010-10-26 10:37:16
Libraries update:
- Logback 0.9.26
- SLF4J 1.6.1
##### 1.3 - 2011-07-09 07:46:50
Logback libraries upgrade from version 0.9.26 to 0.9.29.

Libraries are provided in the bcLogback component V1.3.
##### 2.0 - 2012-11-26 22:28:25
Release notes:

- SLF4J was upgraded from 1.6.x to major version 1.7.2
- Logback was updated to 1.0.7 version
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)
 -   4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   5.1 (obsolete)
 -   5.2 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)