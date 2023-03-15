## <img src='./logo.jpg' width='40' height='40'>tJavaMapsInput

### Overview
An input component that creates a Talend flow from a Map collection. In particular, it generates a flow from the specified Iterable<Map<String, ?>> .

Extremely useful for those who do a lot of their Talend work in Java and need to construct flows from map collections.

Thanks to Carl Walker for inspiring this component.
### Images




#### Release Notes

##### 1.0 - 2013-01-03 22:55:19
An input component that creates a Talend flow from a Map collection. In particular, it generates a flow from the specified Iterable<Map<String, ?>> .

Extremely useful for those who do a lot of their Talend work in Java and need to construct flows from map collections.

The component ZIP includes Test_tJavaMapsInput.zip, which has a test job and supporting routines that you can import into your project for testing and demo purposes.
##### 1.01 - 2013-01-22 20:48:00
* Improved handling of date and numeric types.

NOTE: This component should certainly be compatible with Talend versions from 4.1.2 through 5.1.2 (I have tested with with both versions). It is very likely to be compatible with earlier and later versions as well but that supposition is untested. 
##### 1.02 - 2013-02-03 16:15:47
Fixed CONNECTORS node in tJavaMapsInput_java.xml. Previously, it was not possible to have an incoming OnSubjobOK or OnComponentOK!

NOTE: This component should certainly be compatible with Talend versions from 4.1.2 through 5.1.2 (I have tested with with both versions). It is very likely to be compatible with earlier and later versions as well but that supposition is untested. 
##### 1.03 - 2013-02-07 00:02:43
* Component now specifically consumes an Iterable<Map<String, ?>> which is both more typesafe and more flexible than what I had before (Iterable<Object>).

NOTE: This component should certainly be compatible with Talend versions from 4.1.2 through 5.1.2 (I have tested with with both versions). It is very likely to be compatible with earlier and later versions as well but that supposition is untested. 
### Compatible
 -  5.1 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)