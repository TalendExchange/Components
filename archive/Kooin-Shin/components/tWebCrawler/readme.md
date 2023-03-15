## <img src='./logo.jpg' width='40' height='40'>tWebCrawler

### Overview
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


### Details
1. Search Engine(Wiki/Nature Mag/Time Mag/People Mag/Google/Bing/twitter/Naver/Daum) result crawling, able to be crawling by that.
2. You can configure crawling depth and duration. (Depth is sub level of webpage link. if all of depth of wepage is collected, crawling over)
3. You can use Java regex pattern in keyword pattern.
4. All of result of crawling can saving to specific folder.
5. This component can supports multi-thread crawling. You can set thread count when will be used thread on crawling.(It's very speedy and high-performance way to crawling)
### Images
<a href='./screenshots/v_1.00__3.jpg'><img src='./screenshots/v_1.00__3.jpg' ></a>
<a href='./screenshots/v_1.00__2.jpg'><img src='./screenshots/v_1.00__2.jpg' ></a>
<a href='./screenshots/v_1.00__1.jpg'><img src='./screenshots/v_1.00__1.jpg' ></a>


### Install Instructions
Download actifacts. 
Exetract the component from zip compressed file to temp folder. 
Copy contents of temp folder to TOS components folder where plug-in’s placed. 
And then restart TOS.
Dive into

### Resources
 * <a href=http://www.chaostocosmos.org/>Author's page.</a>

#### Release Notes

##### 1.00 - 2019-03-27 06:44:36
Release ver 1.00 
No limitation.

1. apply Robots.txt policy.
2. add search engines.
2. add option to start page retry count.
3. change thread pool logic and options.
4. HTML save logic improving.
5. add athentication option of proxy setting.

* Used library
webcrawler_1.0.0.jar
### Compatible
 -  6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)
 -   6.4 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)