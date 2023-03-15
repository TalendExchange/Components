## <img src='./logo.jpg' width='40' height='40'>bcLogback

### Overview
This component allows to use the Logback API (using the SLF4J API) to log messages, with the specified log level.

One message is logged by input line. Schema data can be used in the log message.

Note: this component uses the SLF4J API, and no Logback class are direcly used. So, the component can be used with every other logging Framework supported by SLF4J: you just need to replace Logback jar files in the job classpath.
### Images




#### Release Notes

##### 1.0 - 2010-09-01 21:18:04
First revision of the component.

This revision has the same parameters and comportement as the 1.1 version of the tLog4J component.
##### 1.1 - 2010-09-13 08:09:27
Bug correction: the "fatal" log level does not exist in Logback API. That resulted in a compilation error when using it. So this log level has been removed.
##### 1.2 - 2010-10-26 10:36:23
New features:
- optional log message before the data loop, with a custom logging level
- optional log message after the data loop, with a custom logging level
- conditional logging : only row that verify the condition are logged.
- new variable "NB_LOGGED_LINE"

Libraries update:
- Logback 0.9.26
- SLF4J 1.6.1
##### 1.3 - 2011-07-09 07:43:14
New features:
- component is now \\'startable\\' and can be used in a job without input flow.
- component can have an input \\'iterate\\', \\'onSubjobOk\\' or \\'onSubjobError\\' trigger
- component main log can be disabled (to keep only a begin and/or a end log)

Logback libraries upgrade from version 0.9.26 to 0.9.29.
##### 2.0 - 2012-11-26 22:26:25
Release notes:

- SLF4J was upgraded from 1.6.x to major version 1.7.2
- Logback was updated to 1.0.7 version
- Main logging message can now use the SLF4J template format (\\"{}\\"), with parameters
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