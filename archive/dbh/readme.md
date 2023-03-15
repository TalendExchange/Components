# dbh
  Lead Developer, Software analyst, designer, architect, & super-geek. currently involved in BI, reporting, ETL, integration work

     <http://davidbharrison.com>
  <nospam+david@davidbharrison.com>

## <a href='./components/tGroovy (updated)/readme.md'><img src='./components/tGroovy (updated)/logo.jpg' width='40' height='40'> tGroovy (updated)</a>
 :warning: Compatibility not known

This component is an enhancement of twtg's tGroovyRow.  It based on tGroovyRow.  
The updated tGroovyRow works on TOS 6.1 and has a never version of Groovy (2.4.5) bundled with it.

Per twwtg, tGroovyRow is similar to tJavaRow component, except it allows users to write Groovy code.  Component Info:  The input and output rows, as well as the context object, are converted to Groovy maps (java.util.HashMap) with all the groovy goodness associated with maps. Primitive types are boxed into their object representations within the script and unboxed upon leaving the script.  The groovy script is compiled into a class upon first use.  One object of this groovy class is instantiated, stored and reused for each row.  Users have access to modify the groovy class via the “Advanced Settings” panel, and are reminded of their responsibility for all the potentially wonderful and horrible results such modification might cause.   
<img src='./components/tGroovy (updated)/sample.jpg'>
