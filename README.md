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
<p>│   ├── connection.js</p>
<p>│   └── orm.js</p>
<p>│ </p>
<p>├── controllers</p>
<p>│   └── burgers_controller.js</p>
<p>│</p>
<p>├── db</p>
<p>│   ├── schema.sql</p>
<p>│   └── seeds.sql</p>
<p>│</p>
<p>├── models</p>
<p>│   └── burger.js</p>
<p>│ </p>
<p>├── node_modules</p>
<p>│ </p>
<p>├── package.json</p>
<p>│</p>
<p>├── public</p>
<p>│   └── assets</p>
<p>│       ├── css</p>
<p>│       │   └── burger_style.css</p>
<p>│       └── img</p>
<p>│           └── burger.png</p>
<p>│   </p>
<p>│</p>
<p>├── server.js</p>
<p>│</p>
<p>└── views</p>
    <p>├── index.handlebars</p>
    <p>└── layouts</p>
        <p>└── main.handlebars</p>
