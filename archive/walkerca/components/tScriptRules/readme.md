## <img src='./logo.jpg' width='40' height='40'>tScriptRules

### Overview
Version 2.3 supports 5.2.1 and adds Silenty and Leniently checkboxes to the Advanced Tab to control what happens with malformed rules or input

Version 2.2. adds the capability of referencing Talend Routines such as StringHandling or your own validation code packaged as Routines

Version 2.0 is a complete rewrite.  Also see the tScriptRulesLoad component.  The documentation and demo videos are being updated.

A filtering component that will add a reason code and message to the reject output if a rule fails

Rules are created using JEXL, a Java-like scripting language, and paired with the reason code and message

The normal mode of operation will break on the first failure. There is a Run All mode that will create multiple reject rows for each failure.  

Formerly listed as \\\\\\\\\\\\\\"tRules\\\\\\\\\\\\\\" on the Talend Exchange


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-360/screenshot.jpg)
### Images




#### Release Notes

##### 0.1-BETA - 2011-04-13 18:42:16
Enter one or more rules to filter the input like a tFilterRow

Each rule has a reason code and reason message associated with it.  The reason code and message are written out to the reject output along with the data for each record that fails the rule.

The rules are written in Java using the JEXL2 engine.

Keep the values for Java Expression, Reason Code, and Reason Message unquoted.
##### 1.0 - 2011-08-12 14:27:13
Now supports a Run All mode from the Advanced tab.  This mode will produce multiple reject records for each rule failure.

##### 2.0 - 2012-12-22 00:29:50
This is a complete rewrite of the first version that uses more Talend features for configuration (DYNAMIC_SETTINGS) and rules loading. See the tScriptRulesLoad load component. Version 2.0 is also more robust and uniform in its error handling.
##### 2.1 - 2014-03-29 20:22:10
Version to support open source-oriented build
##### 2.2 - 2014-04-01 19:27:56
Adds capability to reference Talend Routines in scripting rules

For example, use this as a Script Expression in Component View to filter non-alphabetic strings

\\\\\\\\\\\\\\"StringHandling.IS_ALPHA(input_row.field1)\\\\\\\\\\\\\\"

Where \\\\\\\\\\\\\\"StringHandling\\\\\\\\\\\\\\" is the built-in Talend Routine
##### 2.3 - 2014-04-07 14:15:01
2.3 Adds sliently and leniently flags to Advanced Settings

Fixes issues:

2\tHandle Empty Input Gracefully
5\ttScriptRules Does Not Work in 5.2.1
6\tUpgrade Unit Tests to JUnit 4

### Compatible
 -  4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   5.1 (obsolete)
 -   5.2 (obsolete)
 -   5.3 (obsolete)
 -   5.4 (obsolete)
 -   5.5 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)