# mongo-scraper-hw

NPR World News Scraper

This Heroku Deployed app allows the user to scrape the latest news from the NPR World News Website Archive.  Specifically the app pulls 1. Title, 2.Link, 3. Summary of a news article.  The user is able to click  the articles and save notes to them- they also have the ability to delete notes.  Notes are saved on the database.  The user can also click Scrape Now rescrape the latest articles and repopulate the page.  The app is deployed to Heroku and utilizes a MongoDB database to store the scraped article data and notes.  

Technologies/Tools Used

Node
HTML
express
mongoose
body-parser
cheerio
request
MongoDB
Javascript
mLab

To Use

Click the deployed Heroku App.  

To use locally, use command "npm install" to install dependent packages, then start mongoDB by typing "mongod" in the command line.  Run mongo and start the server.js.


Link: https://mongo-scraper-bc2018.herokuapp.com

