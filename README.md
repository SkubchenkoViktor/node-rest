# node-rest-mysql

This is a boilerplate with proper for using Node.js with Express to host a RESTful API for a MySQL/MariaDB Database.

## Resources

Developed using a couple resources:

1. Express (http://expressjs.com/en/4x/api.html)
2. MySQL for Node (https://github.com/mysqljs/mysql)
3. RESTAPI Tutorial (http://www.restapitutorial.com/lessons/httpmethods.html)
4. Build a RESTful API Using Node and Express 4 (https://scotch.io/tutorials/build-a-restful-api-using-node-and-express-4)
5. Node 404 (http://stackoverflow.com/a/33310600)
6. RESTful Best Practices (http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api#advanced-queries)
7. Test a Node RESTful API with Mocha and Chai (https://scotch.io/tutorials/test-a-node-restful-api-with-mocha-and-chai)

## Installation

1. `npm install`

2. create a `credentials.js` file in the root of the repo

   ```javascript
   module.exports = {
   	host     : 'localhost',
   	user     : 'me',
   	password : 'secret',
   	database : 'my_db'
   }
   ```

3. OR pass in MYSQL_HOST, etc as evnironment variables (eg. from Heroku's Config Vars)

4. Use Postman or your browser to make requests to the api, at `/api/…`