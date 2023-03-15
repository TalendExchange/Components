## <img src='./logo.jpg' width='40' height='40'>tTikaExtractor

### Overview
tTikaExtractor use Apache TIKA parser to easily extract information from many different formats like (html, pdf, doc, odt, image, audio, video, ...). See http://tika.apache.org/1.0/formats.html for more information about available parsers.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-475/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2012-01-25 17:03:59
This first release parse any document supported by TIKA parser and provide properties to do further processing:
 * TIKA Metadata object (METADATA_OBJ property)
 * TIKA Metadata as as text (METADATA property)
 * Resource content as text (CONTENT property)
 * Resource content as XHTML (CONTENT_XHTML property) which could be used in tExtractXMLField for further extraction

If you have trouble parsing some formats, download the complete tika-app jar file from http://tika.apache.org/download.html and replace the one included in that pack which was modified in order to upload the component to exchange which has probably a limit around 18Mo.
### Compatible
 -  5.0 (obsolete)
 -   5.2 (obsolete)
 -   5.3 (obsolete)
 -   5.4 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)