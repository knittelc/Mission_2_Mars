# Mission to Mars
## Overview
I was hired to automate a web browser to visit different websites to extract data about the Mission to Mars.  I scraped articles with their titles, images of Mars and its hemispheres, and a Mars Facts data table.  The competed work scrapes for the newest featured articles, pictures and tables.  Web scraping is a method used by organizations worldwide to extract online data for analysis.  It also helps to automate tedious tasks for smaller projects.  The outcome is to use these methods and start an HTML portfolio so future companies can see my capabilities.

## Resources
#### Web pages scraped:
- https://data-class-mars.s3.amazonaws.com/Mars/index.html
- https://spaceimages-mars.com
- https://galaxyfacts-mars.com
- https://marshemispheres.com/

#### Software:
- Python
- Jupyter Notebook
- Pandas, BeautifulSoup, Splinter, ChromeDriverManager, Flask, PyMongo, DateTime
- MongoDB
- HTML5/CSS
- Bootstrap 3

## Results
The first app.py, scraping.py, and html index returned the newest Mars article, a featured picture, and the Mars facts table.  
![Initial Mars webpage](https://user-images.githubusercontent.com/102183530/173260853-f65dacfe-fe40-4c03-ad33-089feb837f54.png)
###### Figure 1: The intitial local web page shows, the basic button in a header, the article and title, the featured image and table.

Then I was asked to also add one more bit of scraping to pull in the beautiful shots of the hemispheres of Mars.  After assuring the code worked in Jupyter Notebook (see below); I then refracted and cleaned, while making it into a more useful tool.

![working jupyter code](https://user-images.githubusercontent.com/102183530/173260774-108f9302-1450-45b2-a879-5702e0afe9dc.png)
###### Figure 2:  Started with working Jupyter Notebook code to return the hemisphere images and titles.

After cleaning and updating the html, I also added a picture behind the button, changed the heading color for ease of reading, and added some styling to the table.
![new page top](https://user-images.githubusercontent.com/102183530/173264545-e5c15a0a-afc5-4bd2-b085-4904021060a3.png)
###### Figure 3: Top of the stylized page with the hemispheres (see below).

![hemispheres_mars](https://user-images.githubusercontent.com/102183530/173261035-8ed39e74-7ea7-42d9-9f40-e0be1492cf81.png)
###### Figure 5:  Shows the updated hemispheres and table styling.

It was also nice to see the MongoDB mars_app working in the background.  Here you can see what has loaded into the mars collection.
![Mars DB collection](https://user-images.githubusercontent.com/102183530/173264649-bc15291d-32b8-45ae-baa9-a09c82386b3d.png)
###### Figure 6: MongoDB in action!
