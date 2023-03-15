## <img src='./logo.jpg' width='40' height='40'>tInformixInput

### Overview
Informix Database SQL input

Evolution of Talend's original tInformixInput component in order to use Informix in transactionnal mode with the tInformixConnection, tInformixCommit and tInformixRollback components.

This component has been improved and added to TOS 4.0.0+. So it is now supported on Talend bugtracker.
### Images




#### Release Notes

##### 0.2 - 2009-03-16 21:41:56
First evolution of Talend's tInformixInput component.

In order to use this component, you must first delete Talend's component. If not, there will be a conflict since they have the same name.
##### 0.3 - 2009-03-27 11:28:26
Minor bug correction : trim "dbproperties" before testing if it is empty.

Upgrade of IBM JDBC drivers to revision 3.0 JC3.
This upgrade is needed for using Informix stored procedures and functions (precedent revision's implementation of CallableStatement was bogus).
##### 0.4 - 2009-05-06 10:54:56
- Family information added for 3.1.0 compatibility
- French translation of the component
- Partial translation in other languages
- Cleaning of translation files to remove unused keys

This version is NOT compatible anymore with 3.0.X versions of Talend Open Studio

03/06/2009 : correction of a 3.1.X compatibility problem
### Compatible
 -  3.0 (obsolete)
 -   3.1 (obsolete)