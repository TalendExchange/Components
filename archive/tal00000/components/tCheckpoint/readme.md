## <img src='./logo.jpg' width='40' height='40'>tCheckpoint

### Overview
Checkpointing is a simple way to add some restart and recovery capability to your Talend Jobs.

Talend Enterprise provides some functionality that allows you to checkpoint an OnSubJobOK connector; but there is nothing available to Open Studio. tCheckpoint (used in conjunction with tCheckpointStart and tCheckpointEnd) allows you to modularise your Job in to restartable sections. If your Job does not complete successfully, tCheckpoint will provide sufficient information to allow you to determine if a particular section needs to run your recovery code, does not need to run at all, or should be run normally.

Add a tCheckpointStart to your Job. Set the Checkpoint Directory and, optionally, the Checkpoint File. tCheckpointStart sets the boolean value globalMap.get("tCheckpoint_inRecovery"), allowing you to determine if your Job is in recovery.

Add a number of tCheckpoint, as needed. Each tCheckpoint will set the following boolean values - globalMap.get("tCheckpoint_1_NEEDS_RECOVERY") and globalMap.get("tCheckpoint_1_NEEDS_EXECUTION"). You can use these in IF connectors to determine the code that should be executed. Remember that your recovery code will normally be Order:1. You can also enter Code directly in to the tCheckpoint component, as you would with tJava.

Add a tCheckpointEnd to your Job, to complete a series of checkpoints. You can specify if the checkpoint file should be cleared. It may be helpful during debugging to retain checkpoint file history.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-1162/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2014-06-05 18:01:47
 Checkpointing is a simple way to add some restart and recovery capability to your Talend Jobs.Talend Enterprise provides some functionality that allows you to checkpoint an OnSubJobOK connector; but there is nothing available to Open Studio. tCheckpoint (used in conjunction with tCheckpointStart and tCheckpointEnd) allows you to modularise your Job in to restartable sections. If your Job does not complete successfully, tCheckpoint will provide sufficient information to allow you to determine if a particular section needs to run your recovery code, does not need to run at all, or should be run normally.
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