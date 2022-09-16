# Mission-to-Mars: Module 10 Challenge

## Overview of Project

### Background and Purpose

A junior data scientist, Robin, does freelance astronomy work in her spare time. Her dream is to land a position with NASA one day, so she spends a lot of time visiting sites with news about space exploration, especially the mission to Mars. One day, while reading an article about how much water the red planet may have had in its youth, she has an idea. What if she could write a script that would gather all of the information she searches for in one convenient location, and once she gathered it, what if she could show it off to other astrofiles? If it's polished enough, it may even catch NASA's attention. After thinking about it, Robin is convinced. She wants to gather data about the mission to Mars from all over the web and display it in a central location without spending her free time gathering the data manually. Instead she plans to build a web application that will scrape new data every time she tells it to with the click of a button.

This challenge utilizes skills from Python, HTML, CSS, Flask, MongoDB, and Bootstrap to scrape data from the web, store it into a database, and then use that data to create a new webpage showcasing the following:

1. A link to the latest Mars news
2. A table of basic Mars facts
3. A featured image of Mars from the Jet Propulsion Laboratory at California Institute of Technology
4. Full resolution images of Mars' hemispheres

### Resources

Data Sources:
1. https://redplanetscience.com/
2. https://spaceimages-mars.com/
3. https://galaxyfacts-mars.com/
4. https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars

Software: Anaconda 4.13, Flask 2.2.2, Jupyter Notebook, MongoDB 6.0.0, Mongosh 1.5.4, Python 3.7.6, Visual Studio Code 1.68.1

## Procedure

### Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles

Using BeautifulSoup and Splinter, scrape full-resolution images of Mars’ hemispheres and the titles of those images.

### Deliverable 2: Update the Web App with Mars’ Hemisphere Images and Titles

Using Python and HTML skills, add the code created in Deliverable 1 to the scraping.py file, update the Mongo database, and modify the index.html file so the webpage contains all the information collected in this module, as well as the full-resolution image and title for each hemisphere image.

### Deliverable 3: Add Bootstrap 3 Components

Update the web app to make it mobile-responsive, and add two additional Bootstrap 3 components to make it stand out.
