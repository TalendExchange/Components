## <img src='./logo.jpg' width='40' height='40'>tLDAPAdOutput

### Overview
It's just une little modification of standard tLDAPOutput Component for create/modify password in a Active Directory.

The difference is you can use a column of type byte[].

I have create another component for encrypte the password (and others transformation for a Active Directory): tLDAPPreparAuthAD

Warning : you must use a ssl connection for modify the unicodePwd
  


### Images




#### Release Notes

##### 1 - 2012-01-23 16:27:13
First version work on 4.2.0 and 4.2.1 but must work with newer.
And tested width a AD (active directory) 2003 and 2008

### Compatible
 -  4.2 (obsolete)