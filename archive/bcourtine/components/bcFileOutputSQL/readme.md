## <img src='./logo.jpg' width='40' height='40'>bcFileOutputSQL

### Overview
This component reads the input data and write to the output file the corresponding SQL script.
### Images




#### Release Notes

##### 1.0 - 2010-11-10 20:56:44
First revision:
- INSERT or DELETE script generation
- Objects are transformed into String using toString(). This first revision doesn't manage special objects (binary data, dates, etc.)
##### 1.2 - 2011-03-15 21:07:51
Bug correction : this version can now be used with non nullable columns.
New feature : the output file encoding can now be specified.
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)
 -   4.1 (obsolete)