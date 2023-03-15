## <img src='./logo.jpg' width='40' height='40'>tMemoryMonitor

### Overview
Monitor the memory usage of your running Job, with tMemoryMonitor

Information on the used, total and maximum (see -Xmx) memory of the Java runtime, are written to standard output or, if a warning threshold is reached, to standard error.

Options include 'Enabled', 'Interval' (milliseconds) and 'Warning Threshold Percent %'.

Used in conjunction with your own diagnostic messages, this component will help you to identify where memory is being used within your Job an help you to avoid Out of Memory (OOM) Exceptions.

As well as ensuring that your Job has enough memory, you'll also want to make sure that you do not waste system memory. The Talend Job defaults are -Xms256MB and -Xmx1024MB. As well as some of your Jobs requiring more that 1024MB, some will require less that 256MB. This utility will allow you to observe the peak memory usage and to tune accordingly.

For more information on Java Runtime memory reporting, read http://docs.oracle.com/javase/7/docs/api/java/lang/Runtime.html.

Used memory is totalMemory - freeMemory. Percentages are based on used memory vs. maxMemory.

This component also reports the number of available processors.

Sample output.

tMemoryMonitor_1: using 43MB/246MB (max=910MB/5%) (processors=4)
tMemoryMonitor_1: using 91MB/310MB (max=910MB/10%) (processors=4)
tMemoryMonitor_1: using 260MB/449MB (max=910MB/29%) (processors=4)
tMemoryMonitor_1: using 189MB/442MB (max=910MB/21%) (processors=4)
tMemoryMonitor_1: using 259MB/454MB (max=910MB/28%) (processors=4)
tMemoryMonitor_1: using 216MB/577MB (max=910MB/24%) (processors=4)


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-1202/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2014-08-21 22:35:27
 
### Compatible
 -  1.1 (obsolete)
 -   2.1 (obsolete)
 -   2.2 (obsolete)
 -   2.3 (obsolete)
 -   2.4 (obsolete)
 -   3.0 (obsolete)
 -   3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)
 -   4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   5.1 (obsolete)
 -   5.2 (obsolete)
 -   5.3 (obsolete)
 -   5.4 (obsolete)
 -   5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)