## <img src='./logo.jpg' width='40' height='40'>bcFileOutputOOSpreadsheet

### Overview
Output component in OpenOffice 3.x native format (ODS).

This component uses the ODFDOM library.
### Images




#### Release Notes

##### 0.1 - 2009-12-21 18:01:11
First release.

This version is a beta version, with theses limitations :
- styles are not supported.
- java primitive types are not supported.
- date and number formats are not supported.
- column size is not supported.
- data position in the sheet is not supported.

I will try to release soon an improved version supporting theses functions.
##### 0.2 - 2010-01-11 15:04:49
New features since 0.1 version :

- Specifying the sheet name
- Append data to an existing OpenOffice document :
** Creating a new named sheet in the document
** Using an existing named sheet (clearing the sheet before adding data)
** Using an existing named sheet (adding data after the existing sheet content)
- Specifying an absolute X/Y position in the sheet

The big lacking feature of this version is still that this component does not support "non nullable types" in the Schema. This issue will be solved in the next release.
##### 0.3 - 2010-01-18 17:04:54
Column types are supported :
- primitive types are correctly managed
- Talend numeric column are converted into Open Office numeric cells

Remaining lacking features :
- Date type and pattern are not supported. A date column is converted into a String column by the "toString()" method
- Talend numeric patterns are not managed in the component.

The next release should solve this.
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)