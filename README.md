# HW-NodeExpressHandlebars-Burger

Node Express Handlebars

A burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!). Uses Node and MySQL to query and route data in your app, and Handlebars to generate HTML.

### How it works:

* Eat A Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page adding to the list of devoured burgers!

* The app will store every burger in a database, whether devoured or not.

Heroku App Link:  https://radiant-shore-58098.herokuapp.com/

### Technologies Used:

`Express`

`My SQL`

`Handlebars`

`Node.js`

`MVC Structure (Listed Below For This Project)`

```

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
| 
├── public
│   └── assets
│       ├── css
│       │   └── style.css
│       └── image
│       |   └── burger_background.png
│       └── js
│           └── burgers.js
|
└── views
|   └── layouts
|        └── main.handlebars
|   └── partials
|        └── burgers
|             └── burger-block.handlebars
|   └── index.handlebars
|
├── .gitignore
|
├── package-lock.json
│ 
├── package.json
│
├── README.md
│   
├── server.js

```
