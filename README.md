# Dragons
Archived web setup from 2006ish

This is a Apache Server Sides Includes semi dynamic website(from a free hosting days) using the .shtml file format. Site was massively optimised for use on small data speeds(think dial up 2G tethering)
NOTE: This doesn't work with IIS. Usually this works with index.shtml fine first, but should delete index.htm/l some servers depending on setup might require using default.shtml instead.

index.shtml - is the main landing page, currently has four dynamic sections- news, daily dynamic, new pages, and updated pages.
rss.shtml - provides a RSS feed for the site using the feeds that power index.shtml.
header.shtml & footer.shtml - for compatability reasons redirect to the templating files.
Those files should be left as is.

blank.shtml - is the article page, copy and rename this to make adding new pages a breeze.

design folder - the template files that get changed, in this folder are:
icon.ico - throwback from websites had custom favourite icons
sitelogo.shtml - allowed the site to change the logo dependant on days(used for special events)
bk.jpg - website background image
dragons.css - the main css file for the site

---WIP---
