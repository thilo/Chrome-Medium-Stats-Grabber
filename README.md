# Chrome-Medium-Stats-Grabber

A quick and dirty Google.Chrome extension that grabs story stats from your Medium.com stats page and saves them as a .CSV file. 
* Once installed in Chrome (goto extensions and tick the 'developer mode' option and then add using the 'Load and unpack extension...' button). 
* Log into your Medium.com site, go to your Stats page and scroll to the last item you want the stats for (as Medium uses infinite scrolling). 
* Hit the little !['M icon'](https://github.com/murraygm/Chrome-Medium-Stats-Grabber/raw/master/mediumstatsgrabber/icon.png) 'M' extension icon and it will generate a .CSV file (with "|" delimiters). 

Data structure looks like so: mediumID|title|link|publication|mins|views|reads|readRatio|fans|pubDate

Works for personal and publications.


