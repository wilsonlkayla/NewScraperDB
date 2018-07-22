# NewScraperDB
Homework Assignment for MongoDB
The Vox Article Saver application featured on this page is built using a Mongo Database Scraper. Accomplish the goal of finding articles from Vox.com and give users the ability to save articles to a mongo database.

Technologies Used:
MongoDB
Node
Handlebars
Cheerio
Javascript
HTML
CSS
Bootstrap
jQuery

Description:

The Vox Mongo News Scraper gathers articles based on a custom cheerio scraper of the Vox homepage. The scraped articles are saved into a mongo database. The scraped articles can either be saved or commented on. The comment feature is a separate model that communicates with a comment collection in the mongo database. The comments are then linked with their appropriate article.
