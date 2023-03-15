# jandry
  <nospam+jandry@talend.com>

## <a href='./components/tBufferBatchOutput/readme.md'><img src='./components/tBufferBatchOutput/logo.jpg' width='40' height='40'> tBufferBatchOutput</a>
 :warning: Compatibility not known

Can be set to hold a specific number of records only.  Has 2 modes: continuous, where the buffer will hold on to the last x records and non-continuous which clears the buffer after every x number of records.
<img src='./components/tBufferBatchOutput/sample.jpg'>

## <a href='./components/tNulltoDefault/readme.md'><img src='./components/tNulltoDefault/logo.jpg' width='40' height='40'> tNulltoDefault</a>
 :warning: Compatibility not known

Allows the user to get rid of nulls in the data flow.  The component changes nulls into default values.

byte = 0
short = 0
int = 0
long = 0L
float = 0.0F
double = 0.0
BigDecimal = 0.0
char = \\u0000
boolean = false
String = ""
Date = now

DOES NOT CHANGE

byte[]
List
Object
<img src='./components/tNulltoDefault/sample.jpg'>
