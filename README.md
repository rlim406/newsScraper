# newsScraper

**Description**

1. This app scrapes stories from slashdot.org
2. When the user clicks on scrape stories, headlines from slashdot will load. 
3. The user then has the option to add a comment by clicking the comment button or to save the article by clicking the save article button. 
4. If the user chooses to add a comment, a modal will appear. 
5. The user can then add their comment and submit. 
6. In order for the user to view their comment with the associated saved article, they will have to save the article. 
7. When the user clicks on 'saved articles' in the nav bar they will be redirected to their saved articles. 
8. The user will then have the option to delete their comments and to delete their saved articles. 

**Technologies used**

Handlebars
CSS
Bootstrap
jQuery
Javascript
body-parser
morgan
axios
cheerio
mongoose

**File Structure**

├── models
│   ├── Article.js
│   └── Comment.js
|   └── index.js
│ 
├── public
│   └── app.js
│   └── style.css
|
├── views
│   └── index.handlebars
│   └── saved.handlebars
│   └── layouts
│       └── main.handlebars
|
├── server.js 

