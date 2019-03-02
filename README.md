# Project Title
### Words-Matter-MongoScraper
 Unicef USA Mongo Scraper

## Project Description
Link to the site: [Words-Matter](https://syedascrape-live1.herokuapp.com/)
This web app scrapes news articles from https://www.unicefusa.org/ using Mongoose and Cheerio and lets users view and leave comments on the latest news. 
* also lets users scrape new articles
* clear saved articles 
* view saved artiles
* delete indiviual articles from the saved list
* save write and save notes in the database


### Compatibility logic:
It follows MVC design pattern.
Each scraped article is saved to the application database.
The app scrapes and display the following information for each article:
   * Headline - the title of the article

   * Summary - a short summary of the article

   * URL - the url to the original article

   * Photos - image of the article.

## Getting Started
This app is deplyed to Heroku using mongolab database.
Users are be able to leave comments on the articles displayed and revisit them later. The comments are saved to the database as well and associated with their articles. Users are also able to delete comments left on articles. All stored comments are visible to every user.

* This app when scrapes a site for stories, it makes sure an article isn't already represented in the database before saving it; it doesn't save any duplicate entries.

* It also makes sure not to just clear out the database and populate it with scraped articles whenever a user accesses this site. This way the users are able to see all the comments stored in the database.

### Installing:
Node packages:
After downloading the app, type in npm install in the terminal. It will install the the required packages. 
   * npm install 

## Built With
1. express
2. express-handlebars
3. mongoose
4. cheerio
5. axios
6. node.js
7. mongolab

## Authors
* Syeda Ahmed