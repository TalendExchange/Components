## <img src='./logo.jpg' width='40' height='40'>tHTMLParse

### Overview
This component fetches and parses an HTML document with help from the excellent Java library jsoup (jsoup.org).

A number of elements are extracted from the document together with useful information including the fetch time.

Some elements, for example, Hyperlinks are made available through the jsoup class Elements, allowing you to use the power of jsoup to process these as you wish. When I have time, I'll write some supplemental components that will iterate through these Elements; however, it's simple enough to do this yourself using a component such as tJavaFlex.

The entire document is also made available through the jsoup Document class, allowing you full control over the document.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-1336/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2014-08-21 22:00:25
First release of tHTMLParse
##### 0.2 - 2014-08-26 09:31:20
Amended so that the HTTP Status Code is included as an output row field.

Added support for passing HTTP Header Fields.
### Compatible
 -  4.2 (obsolete)
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