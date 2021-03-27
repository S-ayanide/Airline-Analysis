# Airline Analysis

Airline Analysis Ant Design + Chart JS dashboard with Cube.js

## Run Project

### Setup a Demo Backend

if you already have Cube.js Backend up and running you can skip this step.

Let's start by setting up a database with some sample data. We'll use BigQuery and our [example airline dataset](https://tmpfiles.org/7359/airlines.csv) for this tutorial. You can download and import it by running the following commands.

Cube.js uses environment variables for configuration. It uses environment variables starting with `CUBEJS_`. To configure the connection to our database, we need to specify the DB type and name. In the Cube.js project folder create the .env file with the following:

```
CUBEJS_DB_BQ_PROJECT_ID=PROJECT_ID
CUBEJS_DB_BQ_KEY_FILE=key.json
CUBEJS_DEV_MODE=true
CUBEJS_DB_TYPE=bigquery
CUBEJS_API_SECRET=SECRET
```

### Backend run
To start the cube js backend use this commands
```
$ npm i
$ npm start
```

### Frontend run
To start frontend application use this commands
```
$ cd dashboard-app
$ npm i
$ npm start
```
