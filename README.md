GetMeThatPage
=============

Works just like webgrabber, downloads all the resources i.e. css, js, images from given webpage 
and stores all the files in single folder.

@author - Pramod Khare

@Purpose - This program will grab the whole web page including all its images, css and js files and stores them in a single output directory with all urls in html page modified to point to this directory itself.

@date: 12-Dec-2013

Important Note - Right now, all the files gets stored inside single destination directory (given directory) with no directory structure as of website is maintained, this is because we are not grabbing all pages or multiple pages of a website, we grab only one webpage. So all external links (same domain links) will be modified in downloaded HTML to refer (look into) current directory for all the resources.
 
So when you open downloaded HTML in browser it will open with proper css and images applied, even though in original webpage all css and js files were from different folder hierarchy.

Note - make sure you include jsoup.jar in you classpath when you run this program. You can download the jars from jsoup.org - at this time of writing it was - http://jsoup.org/packages/jsoup-1.7.3.jar or any other location.
