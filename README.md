nodejs-crud
===========

Example of CRUD with sailsjs

>sails generate api user

Open up the model file located at api/models/User.js and modify the attributes block.
Implement a login feature that will authenticate a user and save their user ID in local storage (api/controllers/UserController.js).

Add a user :

>curl --data 'email=john&password=123456' https://nodejs-crud-c9-aquinault.c9.io/user