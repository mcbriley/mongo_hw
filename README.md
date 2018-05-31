# mongo_hw

Had a lot of trouble with this one.

Basically, request and cheerio work together to get the html from the NY Times website. Then, using routes from express, the html is pushed into the handlebars pages in the correct format. To store the articles and notes that are saved, mongoose pulls the necessary info and pushes it into the mongo database.
