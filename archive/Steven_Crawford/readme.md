# Steven_Crawford
  <nospam+Steven_Crawford@Premierinc.com>

## <a href='./components/tFileFetchEnhanced/readme.md'><img src='./components/tFileFetchEnhanced/logo.jpg' width='40' height='40'> tFileFetchEnhanced</a>
 :warning: Compatibility not known

This component extends Talend's tFileFetch to introduce support for RAW Body types on HTTP POST's.  (This means you can send JSON, XML, or whatever)

I also exposed the PostMethod and HTTPClient objects as global variables (access with component name with suffix '_METHOD' and '_CLIENT_STREAM' respectively).
The purpose for this was to provide support for closing the client after finishing with the input. I ran into an issue where the sockets weren't closed properly when iterating over hundreds/thousands of API calls.
<img src='./components/tFileFetchEnhanced/sample.jpg'>

## <a href='./components/tGzipCompress/readme.md'><img src='./components/tGzipCompress/logo.jpg' width='40' height='40'> tGzipCompress</a>
 :warning: Compatibility not known

tGzip compress is a very simple component which compresses a file using gzip.

You can choose whether to keep the default file or remove it after the compression is complete. 
<img src='./components/tGzipCompress/sample.jpg'>

## <a href='./components/tNetinsightInput/readme.md'><img src='./components/tNetinsightInput/logo.jpg' width='40' height='40'> tNetinsightInput</a>
 :warning: Compatibility not known

This component uses Netinsight's XML API to run a report and fetch the resulting file. You can save the file to the local filesystem or write it to cache to be accessed using: ((java.io.InputStream)globalMap.get("tNetinsightInput_1_INPUT_STREAM"))

You can use your own custom xml file or you can use the simple UI to create a GetReportData request with standard data offset (from current date).
<img src='./components/tNetinsightInput/sample.jpg'>

## <a href='./components/tURLDecode/readme.md'><img src='./components/tURLDecode/logo.jpg' width='40' height='40'> tURLDecode</a>
 :warning: Compatibility not known

This component applies URL decoding (UTF-8) to fields using java.net.URLDecoder

I have done basic testing, but this may contain bugs.  I have not seen any in my use.





<img src='./components/tURLDecode/sample.jpg'>
