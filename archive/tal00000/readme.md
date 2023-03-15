# tal00000
  <http://www.TalendByExample.com>
  <nospam+alan.black99@gmail.com>

## <a href='./components/tCheckpoint/readme.md'><img src='./components/tCheckpoint/logo.jpg' width='40' height='40'> tCheckpoint</a>
 :warning: Compatibility not known

Checkpointing is a simple way to add some restart and recovery capability to your Talend Jobs.

Talend Enterprise provides some functionality that allows you to checkpoint an OnSubJobOK connector; but there is nothing available to Open Studio. tCheckpoint (used in conjunction with tCheckpointStart and tCheckpointEnd) allows you to modularise your Job in to restartable sections. If your Job does not complete successfully, tCheckpoint will provide sufficient information to allow you to determine if a particular section needs to run your recovery code, does not need to run at all, or should be run normally.

Add a tCheckpointStart to your Job. Set the Checkpoint Directory and, optionally, the Checkpoint File. tCheckpointStart sets the boolean value globalMap.get("tCheckpoint_inRecovery"), allowing you to determine if your Job is in recovery.

Add a number of tCheckpoint, as needed. Each tCheckpoint will set the following boolean values - globalMap.get("tCheckpoint_1_NEEDS_RECOVERY") and globalMap.get("tCheckpoint_1_NEEDS_EXECUTION"). You can use these in IF connectors to determine the code that should be executed. Remember that your recovery code will normally be Order:1. You can also enter Code directly in to the tCheckpoint component, as you would with tJava.

Add a tCheckpointEnd to your Job, to complete a series of checkpoints. You can specify if the checkpoint file should be cleared. It may be helpful during debugging to retain checkpoint file history.



<img src='./components/tCheckpoint/sample.jpg'>

## <a href='./components/tDimDate/readme.md'><img src='./components/tDimDate/logo.jpg' width='40' height='40'> tDimDate</a>
 :warning: Compatibility not known

<img src='./components/tDimDate/sample.jpg'>

## <a href='./components/tGenPerson/readme.md'><img src='./components/tGenPerson/logo.jpg' width='40' height='40'> tGenPerson</a>
 :warning: Compatibility not known

<img src='./components/tGenPerson/sample.jpg'>

## <a href='./components/tHTMLParse/readme.md'><img src='./components/tHTMLParse/logo.jpg' width='40' height='40'> tHTMLParse</a>
 :warning: Compatibility not known

This component fetches and parses an HTML document with help from the excellent Java library jsoup (jsoup.org).

A number of elements are extracted from the document together with useful information including the fetch time.

Some elements, for example, Hyperlinks are made available through the jsoup class Elements, allowing you to use the power of jsoup to process these as you wish. When I have time, I'll write some supplemental components that will iterate through these Elements; however, it's simple enough to do this yourself using a component such as tJavaFlex.

The entire document is also made available through the jsoup Document class, allowing you full control over the document.



<img src='./components/tHTMLParse/sample.jpg'>

## <a href='./components/tMemoryMonitor/readme.md'><img src='./components/tMemoryMonitor/logo.jpg' width='40' height='40'> tMemoryMonitor</a>
 :warning: Compatibility not known

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



<img src='./components/tMemoryMonitor/sample.jpg'>
