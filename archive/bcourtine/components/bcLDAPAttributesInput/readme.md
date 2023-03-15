## <img src='./logo.jpg' width='40' height='40'>bcLDAPAttributesInput

### Overview
This component is an extension of bcLDAPInputExt :

As the bcLDAPInputExt component, this component will do a research in a LDAP server. But in addition to attribute values (defined in the component schema), for each LDAP object, there are theses information :

- objectclass : list of object classes
- mandatoryattributes : list of mandatory attributes for theses classes
- optionalattributes : list of optional attributes for theses classes
- objectattributes : list of attributes that are really valuated for the current object (at least mandatory attributes)

This component requires the courtinessl library provided in bcLDAPInputExt component.
### Images




#### Release Notes

##### 1.0 - 2010-02-22 15:11:38
First release of this component, successfully tested on a Sun One Directory Server.
##### 1.1 - 2010-02-26 10:45:41
1.0 version does not work in LDAPS mode.
This bug is fixed in this version.

This version has been tested in SunOne Directory Server, and in LDAPS mode on an ActiveDirectory Server.
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)