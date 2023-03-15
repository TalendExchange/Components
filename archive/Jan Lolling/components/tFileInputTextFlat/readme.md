## <img src='./logo.jpg' width='40' height='40'>tFileInputTextFlat

### Overview
This component is dedicated to read text files. 
The component allows to read text files with not stable structures and provide a feature similar to the dynamic schema but for the Open Studio edition.
The configuration can be read from an external file.
### Details
* reads fields with gaps between them
* can configure the columns by the header line (also with regex)
* reduced byte code foodprint
* can apply regex expressions to the field content
* translates the numbers for any country formats
* Can read the field extraction configuration from an external config file.
### Images
<a href='./screenshots/v_4.5__2.jpg'><img src='./screenshots/v_4.5__2.jpg' ></a>
<a href='./screenshots/v_3.5__1.jpg'><img src='./screenshots/v_3.5__1.jpg' ></a>


### Resources
 * <a href=http://jan-lolling.de/talend/components/help/tFileInputTextFlat.pdf>Documentation</a>
 * <a href=https://github.com/jlolling/talendcomp_tFileInputTextFlat>Source Code on Github</a>

#### Release Notes

##### 3.5 - 2015-04-26 15:17:10
* Bug fixed: Exceptions when the configuration file contains disabled columns
* Alternative columns can be set in the configuration file as well as in the component setting to allow reading the content from an alternative column (cascading) if the own value is null
* Text enclosure can be easily switched off with e new option "Use Enclosure"
##### 4.5 - 2019-12-15 18:33:41
* Compatible now with Talend 7.2.1 and following
### Compatible
 -  6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)
 -   6.4 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2