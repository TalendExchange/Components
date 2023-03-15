## <img src='./logo.jpg' width='40' height='40'>tInformixOutput

### Overview
Informix Database SQL output

Evolution of Talend's original tInformixOutput component in order to use Informix in transactionnal mode with the tInformixConnection, tInformixCommit and tInformixRollback components.

Warning : this component is built using a skeleton in main JET template, whose path is relative. So, it MUST be placed in the "plugins/org.talend.designer.components.localprovider_VERSION/components" folder. If not, the component template won't compile !

This component has been improved and added to TOS 4.0.0+. So it is now supported on Talend bugtracker.
### Images




#### Release Notes

##### 0.2 - 2009-03-16 21:44:13
First evolution of Talend's tInformixOutput component.

In order to use this component, you must first delete Talend's component. If not, there will be a conflict since they have the same name.

BOGUS REVISION. Use 0.3 revision or above.
##### 0.3 - 2009-03-27 11:31:01
Minor bug correction : trim "dbproperties" before testing if it is empty.

Major bug correction : 0.2 revision did not compile !
##### 0.4 - 2009-05-06 10:55:37
- Family information added for 3.1.0 compatibility
- French translation of the component
- Partial translation in other languages
- Cleaning of translation files to remove unused keys

This version is NOT compatible anymore with 3.0.X versions of Talend Open Studio

03/06/2009 : correction of a 3.1.X compatibility problem
### Compatible
 -  3.0 (obsolete)
 -   3.1 (obsolete)