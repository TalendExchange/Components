## <img src='./logo.jpg' width='40' height='40'>BRules

### Overview
A collection of Java routines for validation, formatting, and logic for use in Talend Open Studio

Software license: Apache License, Version 2.0

http://www.apache.org/licenses/LICENSE-2.0



![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-354/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2011-03-22 02:44:29
This version includes a function "isPhoneNum" and a variation that allows specification of a "loose" setting

There is a urlPath in the BRules_0.1 properties file containing a path to a user directory.

##### 0.2 UPDATE - 2011-03-31 11:16:28
Added all() and xor() functions for checking if a group of fields is

1) All set - use the all() function
2) Only one is set - use the xor() function

For a great shorthand technique, use the following import in a tJava component

Advanced settings > import

import static routines.BRules.all;
import static routines.BRules.xor;

Version 0.2 uses the StringUtils class from the Commons Lang 3 library.
##### 0.3 - 2011-05-12 16:04:24
Update to library

Includes

* New XML validation routines - isXML() checks for well-formedness
* New character set routines - okChars() verifies a string against a target charset
* New String check routine - isBlank() tests for null, empty string, and whitespace

##### 1.0 - 2011-06-08 01:13:47
Include the toCharset() method for converting Strings from one character set to another

For example, the Unicode 'My Company\\u2122' where \\u2122 is the trademark symbol is converted to 'My CompanyTM' where 'TM' is the trademark symbol represented in Windows Latin-1 (Cp1252)

toCharset() also handles unmappable characters gracefully using a specified character.  An ASCII string can be formed with the space character replacing unmappable Unicode or UTF-8 characters.  Multi-byte sequences are handled.

Version 1.0 also re-packages the routines in a more general purpose project that includes a set of unit test jobs.  It is recommended that the test suite be run after import.
##### 1.1 - 2011-07-06 00:59:03
Adds functions isJSON() and hasJSONPath() to assist tFileInputJSON

isJSON() determines whether or not a string is in JSON format

hasJSONPath() determines whether or not a JSON string contains objects referenced by a JSONP expression

Rewrote charset functions to support Java 5
##### 1.2 - 2011-11-13 19:29:14
Added pad() routine that will add spaces to the left of a string and trimLeadingZeros() that will return a String with any leading zeros stripped off.
##### 1.3 - 2014-02-01 14:05:14
A repackaging of BRules 1.2 with a minor fix to the code completion tags

Also available on the Maven Central Repository

Visit search.maven.org
##### 1.4 - 2014-02-02 21:20:51
Added pad() methods
Improved documentation for code assist
##### 1.5 - 2014-02-09 21:58:01
A set of ageInYears functions were added that computes the number of years elapsed based on today\\'s date or a specified date.  Example uses include a person\\'s age, anniversary date, or contract term.

Several listToString functions were added to convert a java.util.List to a String.
##### 1.6 - 2014-07-30 14:16:34
 
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
 -   5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)