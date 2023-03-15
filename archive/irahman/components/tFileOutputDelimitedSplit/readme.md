## <img src='./logo.jpg' width='40' height='40'>tFileOutputDelimitedSplit

### Overview
This component extends tFileOutputDelimited so that it splits output into multiple files when any arbitrary condition is met.

The standard component splits every N rows; this version starts a new file when any arbitrary condition is met AND/OR the number of rows reaches the limit. Note this means that if both condition and row limit are required, then rows in file can exceed the limit - file will keep growing until the condition is also met.

The use case that drove this change: split output file into manageable chunks as defined by # rows, but without splitting files in the middle of a logical 'group' of rows, where a group was defined as a consecutive set of rows with the same value in a given field. New file is started when current max rows is exceeded AND not in middle of 'group'.
### Images




#### Release Notes

##### 1.0 - 2011-04-27 10:14:48
This component extends tFileOutputDelimited so that it splits output into multiple files when any arbitrary condition is met.

The standard component splits every N rows; this version starts a new file when any arbitrary condition is met AND/OR the number of rows reaches the limit. Note this means that if both condition and row limit are required, then rows in file can exceed the limit - file will keep growing until the condition is also met.
### Compatible
 -  4.1 (obsolete)