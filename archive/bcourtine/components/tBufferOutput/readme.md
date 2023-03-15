## <img src='./logo.jpg' width='40' height='40'>tBufferOutput

### Overview
Output buffer

Evolution of Talend's original tBufferOutput component in order to add a "empty global buffer" checkbox.

If checked, the buffer will be cleared before adding data rows. So, several couples "tOutputBuffer/tInputBuffer" can be used in the same job.

Warning : DO NOT use chains "tInputBuffer => ... => tOutputBuffer" in your jobs. There will be a MemoryException. You can do that chain with the tBufferCopyInput component.

Warning : the "clean option" of this component is executed in the begin jet template. So, chronologicaly, it will be the first thing done in the subjob.
So, in a chain "tBufferCopyInput => ... => tOutputBuffer", to get a clean output buffer before writing data, you MUST use the tBufferCopyInput clean option.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-152/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2009-05-07 13:19:58
Initial revision.
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)