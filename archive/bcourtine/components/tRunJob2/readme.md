## <img src='./logo.jpg' width='40' height='40'>tRunJob2

### Overview
This component is a variation of the tRunJob component.

In the original tRunJob component, you can get the child job output (with a tBufferOutput component in the child job), but you can't send data rows to the child job.

As the original tRunJob component, context parameters can be sent to the child job.

This tRunJob2 component does the contrary : you can send data rows to the child job (with a tBufferOutput in the parent job, and a tBufferInput in the child job), but you can't get data from the child job.

User manual :
1) In the parent job, send data rows to a tOutputBuffer component : They will be automatically copied in the globalBuffer of the child job
2) In the child job, use a tInputBuffer to get theses data rows

See the screenshot for an example.

DEPRECATED COMPONENT : consider using the tRunJobRow component instead.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-153/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2009-05-07 14:49:37
Initial revision
### Compatible
 -  3.1 (obsolete)