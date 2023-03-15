## <img src='./logo.jpg' width='40' height='40'>hiNameProcessing

### Overview
The Human Inference Name Processing component gives you the ability to split names into their name elements. So the name "ing. Bas W.B. van Reeuwijk" will be split into

QualificationPreceding: ing.
GivenNames: Bas
GivenNamesInitial: W.B.
SurnamePrefixFirst: van
SurnameFirst: Reeuwijk

The component supports the following countries: Netherlands, Belgium, France, Germany and United Kingdom. It allows you to check the gender of a person and whether it is a person or an organisation. 

Requirements: Access to a Human Inference server, Human Inference java connector.

Notes on usage:

1) The reliability code gives a reliability status of (1 = correct, 2 = doubtfull, 3 = probably incorrect)
2) The resultcodes of the standardisation are put into a string in the form of
[code1]|[remark1]|[message1];[code2]|[remark2]|[message2];...;[codeN]|[remarkN]|[messageN]; It is therefore recommended to use the tNormalize and tExtractDelimited to get all the details out of the standardisation (see screenshot)
3) Out of one name multiply rows can be generated when the name passed to the component contains more than one name.



![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-216/screenshot.jpg)
### Images




#### Release Notes

##### 2.0 - 2009-11-05 12:46:07
First publicly available version.
##### 2.1 - 2010-08-24 12:29:53
Tested for 4.1 and updated Human Inference Libraries
### Compatible
 -  3.0 (obsolete)
 -   3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)
 -   4.1 (obsolete)