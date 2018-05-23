# SERN-boilerplate

Sequelize, Express, React, Node.js

React.js and server run concurrently. Built for easy deployment.

'yarn install' in main folder and inside client before running with 'yarn start' in main folder.

Run yarn build inside of client before deploying.

Configure db/config/config.json to local specifications

Sequelize does not create the initial database.  If running locally run these two lines of code into mysql workbench before starting server:

DROP database IF EXISTS database_name;
CREATE DATABASE database_name;

db/models/user.js contains code of an example sequelize model.