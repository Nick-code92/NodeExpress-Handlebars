# NodeExpress-Handlebars
This a simple burger app where users can input a new item to the database and then later update that item. The app also allowed the uses boolean values to determine where eat database item should appear on the page. The app use Node and MySQL to query and route data in the app, and Handlebars to generate your HTML.

## Built With
* MySQL
* Node
* Express 
* Handlebars


### FUNCTIONALITY
Create new hamburger to put in the "Available Burgers" section -Render the hamburger table into either the "Available Burgers" section or the "Devoured Burgers" section -Update each hamburger to indicate it has been eaten or Remove burger by Deleting. 



#### Directory structure
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


[Repository](https://github.com/Nick-code92/NodeExpress-Handlebars)  
[Heroku](https://agile-waters-06984.herokuapp.com/)

## Author

[Nikddimos Gebregiorgis](https://github.com/Nick-code92)



