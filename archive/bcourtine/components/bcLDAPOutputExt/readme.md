## <img src='./logo.jpg' width='40' height='40'>bcLDAPOutputExt

### Overview
Extension of Talend tLDAPOutput (3.2.3).

This extension add the following features :
- in TLS mode, a password can be provided to open the certificate file
- in LDAPS and TLS mode, certificate validation can be desactivated (all certs are accepted).

This extension needs the "courtinessl" jar (included in bcLDAPInputExt) which is an evolution of "talendssl".

This component was developed for this usecase :
- when creating a user in Active Directory server, the password can be set ONLY IF the connection is secured. The Active Directory was an internal "auto-certified" server.
### Images




#### Release Notes

##### 1.0 - 2010-02-17 22:18:22
Stable 1.0 revision.
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)