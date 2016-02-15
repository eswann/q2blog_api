## Q2 Blog API

[![Build Status](https://travis-ci.org/eswann/q2blog_api.svg?branch=master)](https://travis-ci.org/eswann/q2blog_api)

###On a Mac, after you clone:

$> cp config.json.example config.json

Change config.json as appropriate for your rethinkdb.


###Install package dependencies:

$> npm install


###If Rethink is not installed
Install RethinkDB:
https://www.rethinkdb.com/docs/install/


Open a terminal and start the server:
$> rethinkdb


###If the db is new and needs initialization:

$> node initdb.js



###Start the node server:

$> npm start


