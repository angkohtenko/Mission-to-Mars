# Mission to Mars
## Overview of the project
The goal of the project was to build flask app which will scrape latest news about Mars mission and images from webpages:
- redplanetscience.com
-	galaxyfacts-mars.com
-	spaceimages-mars.com
-	data-class-mars-hemispheres.s3.amazonaws.com

To realize the project I used flask, BeatifullSoup, splinter libraries. I stored scrapped data in MongoDB and built webpage using Bootstrap.

## Results
First of all, I’ve created separate functions for scrapping:
-	latest news from [redplanetscience.com](redplanetscience.com)
-	featured image from [spaceimages-mars.com](spaceimages-mars.com)
-	table with facts related to Mars and Earth from [galaxyfacts-mars.com](galaxyfacts-mars.com)
-	high-resolution images of Mars hemispheres from [data-class-mars-hemispheres.s3.amazonaws.com](data-class-mars-hemispheres.s3.amazonaws.com)

Then I’ve created new database in MongoDB to store all scrapped data.

Using Flask, I wrote the app that can scrape all listed data and save it to database by clicking the button “Scrape New Data”.

I used Bootstrap to build mobile-responsive webpage and display all data to user.

![image](https://github.com/angkohtenko/Mission-to-Mars/blob/main/templates/Scrapping_page.png)
