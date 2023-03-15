# walkerca
  <http://www.bekwam.com>
  <nospam+carl@bekwam.com>

## <a href='./components/tScriptRules/readme.md'><img src='./components/tScriptRules/logo.jpg' width='40' height='40'> tScriptRules</a>
 :warning: Compatibility not known

Version 2.3 supports 5.2.1 and adds Silenty and Leniently checkboxes to the Advanced Tab to control what happens with malformed rules or input

Version 2.2. adds the capability of referencing Talend Routines such as StringHandling or your own validation code packaged as Routines

Version 2.0 is a complete rewrite.  Also see the tScriptRulesLoad component.  The documentation and demo videos are being updated.

A filtering component that will add a reason code and message to the reject output if a rule fails

Rules are created using JEXL, a Java-like scripting language, and paired with the reason code and message

The normal mode of operation will break on the first failure. There is a Run All mode that will create multiple reject rows for each failure.  

Formerly listed as \\\\\\\\\\\\\\"tRules\\\\\\\\\\\\\\" on the Talend Exchange



<img src='./components/tScriptRules/sample.jpg'>

## <a href='./components/tScriptRulesLoad/readme.md'><img src='./components/tScriptRulesLoad/logo.jpg' width='40' height='40'> tScriptRulesLoad</a>
 :warning: Compatibility not known

A component that works with tScriptRules to provide a rule list.  In tScriptRules, a list of rules written in Javascript can be maintained in a table accessible through the Component View.  tScriptRulesLoad enables the rules to be loaded from another source such as a flat file, tFixedFlowInput, database, or even a web service.  This is accomplished using the normal Talend mechanisms (tFileInputDelimted -> tScriptRulesLoad).



<img src='./components/tScriptRulesLoad/sample.jpg'>
