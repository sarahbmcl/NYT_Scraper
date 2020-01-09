# New York Times Scraper

<!-- * [NYT_Scraper] () -->

## Application

Whenever a user visits the site, the New York Times Scraper scrapes stories from New York Times and displays them for the user to view. Each scraped article should is saved to the application database.  This code connects mongoose to the remote mongolab database if deployed, but otherwise will connect to the local mongoHeadlines database on the computer.

When scraping, the app displays the following information for each article:
- Headline
- Summary
- URL

Users are able to leave comments on the articles displayed and revisit them later. Comments are saved to the database as well and associated with their articles. Users are able to delete comments left on articles. All stored comments are visible to every user.

## Technologies Used
- Axios
- BodyParser
- Cheerio
- CSS
- Express Web Server
- Express Handlebars
- JavaScript
- MongoDB
- Mongoose
- Node
