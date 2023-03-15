# saburo
  <http://www.powerupbi.com/talend>
  <nospam+francesco@air2.it>

## <a href='./components/Facebook Application Insights Component/readme.md'><img src='./components/Facebook Application Insights Component/logo.jpg' width='40' height='40'> Facebook Application Insights Component</a>
 :warning: Compatibility not known

A component that connects to Facebook to retrieve application information (the kind of information that Facebook calls "Insights").

The component uses the application id and secret code (they are available to app admins) to obtain an access token, then it uses the access token to retrieve the information.

The process will be properly documented soon, with some examples.
Check the associated links for more details

Note : This does NOT retrieve personal feeds, wall feeds etc as this kind of activity requires a different OAuth token that cannot be retrieved without human intervention (at least based on my knowledge)



<img src='./components/Facebook Application Insights Component/sample.jpg'>

## <a href='./components/tCacheInput/readme.md'><img src='./components/tCacheInput/logo.jpg' width='40' height='40'> tCacheInput</a>
 :warning: Compatibility not known

Reads data cached using a tCacheOutput component.

It can read a memory buffer or a cache file.
<img src='./components/tCacheInput/sample.jpg'>

## <a href='./components/tCacheOutput/readme.md'><img src='./components/tCacheOutput/logo.jpg' width='40' height='40'> tCacheOutput</a>
 :warning: Compatibility not known

Stores data in a memory buffer and / or to disk. Buffers can be loaded incrementally using iterations.

Memorized data can then be consumed using a tCacheInput component.
The current release does not use data compression.

<img src='./components/tCacheOutput/sample.jpg'>

## <a href='./components/tRoundRobin/readme.md'><img src='./components/tRoundRobin/logo.jpg' width='40' height='40'> tRoundRobin</a>
 :warning: Compatibility not known

Performs a round robin distribution of the input to all the output connections.
It may help in big database loads, where parallelization can improve performances.
<img src='./components/tRoundRobin/sample.jpg'>

## <a href='./components/tSerialInput/readme.md'><img src='./components/tSerialInput/logo.jpg' width='40' height='40'> tSerialInput</a>
 :warning: Compatibility not known

tSerialInput reads data from the serial port and it produces an output data flow with a single tString field, containing the line received.

Lines are terminated by a configurable terminator (default is \
 ).

It is based on the gnu.io RXTX library which has to be installed separately as it requires a different jar depending on your operating system (to access the hardware, such as comports, java needs JNI, which is specific for each architecture) 



<img src='./components/tSerialInput/sample.jpg'>

## <a href='./components/tTimeGenerator/readme.md'><img src='./components/tTimeGenerator/logo.jpg' width='40' height='40'> tTimeGenerator</a>
 :warning: Compatibility not known

tTimeGenerator is a component that can generate simple time dimension tables for YEAR, QUARTER and MONTH levels.

A sample job demonstrates how to create 3 separate tables or to combine them into a single time dimension table.

Often in BI projects it is more handy to have separate levels in order to perform relative time calculations or feed picklists for user prompts.   



<img src='./components/tTimeGenerator/sample.jpg'>

## <a href='./components/World Bank data webservice connectors/readme.md'><img src='./components/World Bank data webservice connectors/logo.jpg' width='40' height='40'> World Bank data webservice connectors</a>
 :warning: Compatibility not known

The World Bank publishes an interesting (and huge) set of data regarding countries.
This data (gni per capita, agriculture indicators, pollution, energy, instruction, country development indexes etc) is publicly accessible via some webservice interfaces.

I created a set of 4 components to ease the task of getting that data and eventually loading it into a data warehouse.

Visit the world bank website for more information, or the associated link for more info on the component itself.

Currently a demo job is also available in Exchange



<img src='./components/World Bank data webservice connectors/sample.jpg'>
