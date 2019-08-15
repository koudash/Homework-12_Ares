# Ares

<p>A single HTML page was created to display various info. related to Mars. Such info. was lively retrieved simply by clicking the <strong>Scrape New Data</strong> button on HTML, which sent instructions to scraping app (<i>scrape_mars.py</i>) through connecting with "scrape()" router of Flask server. Data were scraped from various websites, being <strong>Latest Mars News</strong> from <a href="https://mars.nasa.gov/news" alt="NASA Mars News">NASA Mars News</a>, <strong>Featured Mars Image</strong> from <a href="https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars" alt="Jet Propulsion Laboratory">Jet Propulsion Laboratory</a>, <strong>Mars Weather</strong> from <a href="https://twitter.com/marswxreport?lang=en" alt="Mars Weather on Twitter">Mars Weather on Twitter</a>, <strong>Mars Facts</strong> from <a href="https://space-facts.com/mars/" alt="Space Fact">Space Fact</a>, and <strong>Mars Hemispheres</strong> from <a href="https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars" alt="USGS Astrogeology">USGS Astrogeology</a>. Scraped data were stored in mongoDB. The latest data record was then retrieved from database by "index()" router of Flask app and passed to HTML for display.</p>
<img src="./static/images/HTML Screenshot.png" alt="screenshot">

