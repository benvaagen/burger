# Eat Da Burger - Week 12
deployed: https://git.heroku.com/eat-da-burger-benjamin-vaagen.git

Utilized:node.js handlebars express
Additionally: mysql jawsdb html bootstrap

The assignment was to create a burger logger using MySQL, Node, Express, Handlbars, and an ORM- while following the MVC ( Model-View-Controller) design pattern.

#### Requirements:
*When a burger is ordered, the app will display the burger on the left side of the page- waiting to be devoured.
*Each Burger on the left side must have a devour button which, when clicked, the burger is moved to the right side of the page.
*The app must store every burger in the database, whether or not it has been devoured.
*Assignment must be deployed using both Heroku and Github

#### NPM PACKAGES UTILIZED:
*express
*express-handlebars
*mysql
*body-parser
*dotenv

#### Directory structure

All the recommended files and directories from the steps above should look like the following structure:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```
### A Note From the Creator:
I found this assignement very difficult. When we started out on the front end, the file structure was so simple, with a index.html and then a nice concise assets folder. With all that we have learned in the last few weeks, the file structure has become so much more complicated. My tutor (who is literally an Angel) assures me that in the coming weeks, I am going to really grasp everything that we utilized in the completion of this homework- and I can't wait for that!

I am very proud about how far I have come in the last 4 months! I never wouldn've have thought that I would be capable of utilizing the multitude of concepts that we now use on a daily basis. This bootcamp has been lifechanging and hard, but my instructor told me on day one, even though I was terrified and confused beyond belief, "Ben, you are going to be a developer." I didn't believe it then, but I am beginning to think that these people have a reason for saying and doing everything that they do- and with that in mind, I myself am starting to believe- I will be a developer.
