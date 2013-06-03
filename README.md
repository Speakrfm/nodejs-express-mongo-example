##MongoDb Express nodejs and heroku Blog example

### Install packages 
`sudo npm install express express-messages mongoose sass ejs`


### View the latestest from registry.npmjs.org
`npm view <package-name> version`

Fix your package.json, `heroku requires to define all packages and versions`! Else you have an exeption!

### Update
`sudo npm install -d`

`npm list`

`npm list --depth=0`

###Deploy in heroku
`heroku create `

`heroku apps:rename your_app_name`

`heroku addons:add mongolab `

`heroku addons:open mongolab`

`git push heroku`

`heroku open`


### Run on localhost
node app.js

`http://localhost:3000`
visit: [http://localhost:3000](http://localhost:3000)

Folked by: https://github.com/cmarin/MongoDB-Node-Express-Blog

Edited by:[@yannis_kolovos](https://twitter.com/yannis_kolovos)