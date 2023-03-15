## <img src='./logo.jpg' width='40' height='40'>tFileFetchEnhanced

### Overview
This component extends Talend's tFileFetch to introduce support for RAW Body types on HTTP POST's.  (This means you can send JSON, XML, or whatever)

I also exposed the PostMethod and HTTPClient objects as global variables (access with component name with suffix '_METHOD' and '_CLIENT_STREAM' respectively).
The purpose for this was to provide support for closing the client after finishing with the input. I ran into an issue where the sockets weren't closed properly when iterating over hundreds/thousands of API calls.
### Images




#### Release Notes

##### 1 - 2014-11-20 18:53:36
First release
### Compatible
 -  5.3 (obsolete)