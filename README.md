MEAN Template
-------

Simple set up for future single page MEAN stack projects.

###File Structure
```
- app
  - models/
    - nerd.js <!-- the nerd model to handle CRUD -->
  - routes.js
- config
  - db.js
- node_modules <!-- created by npm install -->
- public <!-- all frontend and angular stuff -->
- css
  - js
    - controllers <!-- angular controllers -->
      - MainCtrl.js
      - NerdCtrl.js
    - services <!-- angular services -->
      - NerdService.js
    - app.js <!-- angular application -->
    - appRoutes.js <!-- angular routes -->
- img
  - libs <!-- created by bower install -->
  - views
    - home.html
    - nerd.html
    - geek.html
    - index.html
- .bowerrc <!-- tells bower where to put files (public/libs) -->
- .gitignore
- README.md
- bower.json <!-- tells bower which files we need -->
- package.json <!-- tells npm which packages we need -->
- server.js <!-- set up our node application -->
```

###Set Up
```
$ git clone git@github.com:kevinlanzon/MEAN-template.git
$ cd MEAN-template
$ npm install
$ bower install
$ node server.js
visit http://localhost:8080
```
