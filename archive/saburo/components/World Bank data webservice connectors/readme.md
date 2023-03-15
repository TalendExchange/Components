## <img src='./logo.jpg' width='40' height='40'>World Bank data webservice connectors

### Overview
The World Bank publishes an interesting (and huge) set of data regarding countries.
This data (gni per capita, agriculture indicators, pollution, energy, instruction, country development indexes etc) is publicly accessible via some webservice interfaces.

I created a set of 4 components to ease the task of getting that data and eventually loading it into a data warehouse.

Visit the world bank website for more information, or the associated link for more info on the component itself.

Currently a demo job is also available in Exchange


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-396/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2011-08-01 19:22:57
First release.
Sorry, the icons are really ugly, I promise I will improve them.
Documentation will be released in the next days.
##### 0.2 - 2011-08-02 09:13:45
- Added Indicator topics filed (if more than 1 topi is associated, values are comma separated)
- improved a bit the icons (ok, it\\'s official, I am useless with icons)
- Improved parameter management


Note : if you get an error about getSubTable method, it\\'s probably because TOS di not refresh the powerup-worldbank-xx.jar file. It should copy it automatically from the component\\'s directory to <talend base dir>/lib/java , but sometimes, if a file already exists there, it does not replace it. To solve the issue -should it happen to you-, just copy there the file manually.
##### 0.3 - 2011-08-03 09:24:24
- Fixed a small bug (was fetching capitalcity instead of capitalCity and iso2code instead of iso2Code ) in country component
##### 0.4 - 2011-08-30 16:57:28
Fixed a small typo and created table  generation sql script for mysql and also exported table schemas (repository objects) for the studio.
See links 
### Compatible
 -  4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)