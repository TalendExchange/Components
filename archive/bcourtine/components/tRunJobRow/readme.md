## <img src='./logo.jpg' width='40' height='40'>tRunJobRow

### Overview
This component was created to run another job, sending to the subjob data rows, and getting back result rows :

- input and output schemas of the subjob can be different (technically, the tRunJobRow component has only an output schema)
- input and output row line numbers can be different

To work fine, this component NEEDS the tBufferCopyInput component.

User manual and explanations :
1) In the main job, data rows are sent to a tBufferOutput
2) In the subjob, data rows are read with a tBufferCopyInput. This component also cleans the global buffer for the next tBufferOutput
3) In the subjob, output data rows are sent to a tBufferOutput

See the screenshot for a real example.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-155/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2009-05-08 08:11:55
Initial revision
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)