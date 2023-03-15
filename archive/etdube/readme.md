# etdube
  <nospam+etienne.dube@boreal-is.com>

## <a href='./components/tPostgresqlSequence/readme.md'><img src='./components/tPostgresqlSequence/logo.jpg' width='40' height='40'> tPostgresqlSequence</a>
 :warning: Compatibility not known

This component is used to retrieve a value from a DB sequence in PostgreSQL. The function call used to get the sequence value is configurable, so for all intents and purposes this component simply calls a DB function that returns a long or integer for every input row, and puts that number in the specified output column (must be a Long or Integer column).

<img src='./components/tPostgresqlSequence/sample.jpg'>
