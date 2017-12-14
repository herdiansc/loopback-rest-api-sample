# README #

A REST API Server implemented by loopback.

### What is this repository for? ###

* API Server
* Version: 1.0.0

### How do I get set up? ###

* Clone this repo
* Import mysql schema: `mysql_schema/Dump20170613.sql`
* Update datasource configuration: `server/datasources.json`
* Execute this command from project root to install project dependency: `npm install` 
* Execute this command from project root to run app in local: `node .`
* API will be accesible in: `http://0.0.0.0:3000/api/v1/[resource]`