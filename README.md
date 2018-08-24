## Eat-da-burger!!!
<br>
<br>

Before You Begin
Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

<br>
Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.

<br>
Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page.

<br>
The app store's every burger in a database, whether devoured or not.

<br>
## Technologies Used
Node.js
MySql
Express
Handlebars
<br>
<br>

## File Setup
<br>
<p>├── config</p>
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
