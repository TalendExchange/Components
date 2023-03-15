# ChaosToCosmos
  Hi all~ 

I am developer of hooking on Talend. My major field of programming is Java that is involving not only developing ETL but also Web, Application, Network developing etc. I imagine that all of developers work with interactive co-working.

I wish good days always be with you :)

     <nospam+chaos930@gmail.com>

## <a href='./components/tWebCrawler/readme.md'><img src='./components/tWebCrawler/logo.jpg' width='40' height='40'> tWebCrawler</a>
 :warning: Compatibility not known

This component is dedicated for crawling HTML content from website.
you can config that component be needed option field such as "Search Engine", "Crawling URL", "Webpage keyword pattern", "Crawling depth", "Crawling Duration", "Save HTML"... etc in Basic settings.
you can set Advanced setting where, from this tab, you are select varius option to improve tWebCrawler component.
you can connect crawling result to other component as output connection that able to be accepted to process data. Through doing this, you are able to process crawling data for what you need to processing.
During component is running, Crawler component collect web content and deliver content to connected other components.
Output schema setting is able to process what you want to.


Output of crawling schema is involved inforamtion of follows.

URL - crawling URL
KEYWORD - keyword from user
MATCH - match count in content
HTML - collected HTML page
TEXT - extract text from HTML page
COOKIE - cookie of collected HTML
CHARSET - charset of HTML page
FILENAME - filename of HTML
LAST_MODIFIED - lastmodified value of HTML header
CURRENT_DATE - timestamp of time of crawling HTML


<img src='./components/tWebCrawler/sample.jpg'>
