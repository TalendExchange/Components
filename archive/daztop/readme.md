# daztop
  <http://www.bt.com>
  <nospam+daztop@rocketmail.com>

## <a href='./components/tUnpivotRow/readme.md'><img src='./components/tUnpivotRow/logo.jpg' width='40' height='40'> tUnpivotRow</a>
 :warning: Compatibility not known

Converts data in the form:

keyHeader, Column1, Column2, Column3
keyVal1, value11, value12, value13
keyVal2, value21, value22, value23

into the form:

keyval1, column1, value11
keyval1, column2, value12
keyval1, column3, value13
keyval2, column1, value21
keyval2, column2, value22
keyval2, column3, value23

It allows as many key columns to be selected as necessary, with all other columns being treated as pivot columns.

An option also exists to skip null/empty values.  E.g. with it enabled, the following:

keyHeader, Column1, Column2, Column3
keyVal1, value11, , value13
keyVal2, , value22, value23

would become:

keyval1, column1, value11
keyval1, column3, value13
keyval2, column2, value22
keyval2, column3, value23

NOTE: I started this component based around a similar one for Perl written by plegall.  The process for this version of the component is slightly different though, which is why I've posted this separately.

TODO: A little validation may be required when values contain escaped quotes - this version is very specific to my requirements.
TODO2: I was unable to find a way to dynamically set the output schema based on the input values.  Some validation is performed to try and ensure that out = key values plus names/values, however there are some scenarios within TOS that cause the validation to be ignored.
<img src='./components/tUnpivotRow/sample.jpg'>
