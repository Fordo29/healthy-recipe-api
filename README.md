# Healthy Recipe API
- Deployed API on Heroku [here](https:) <br>
- Frontend Repo [here]() <br>

## Background

This server was created to accompany the user interface of 'DLCA Cookbook Application', a personal project to support individuals navigate through healthy recipes. This server was written in JavaScript using Express and Node.

## Installation Instructions

1. Clone down this repo to your local machine:
    - `git@github.com:Fordo29/healthy-recipe-api.git`
2. Change into the new directory:
    - `cd healthy-recipe-api`
3. Install the dependencies:
    - `npm install`
4. To fire up the server, run:
    - `node server.js` or `nodemon server.js`(if you have nodemon installed)
5. In the browser or postman, use the following endpoints with the base URL: http://localhost:3001/ to retrieve data. 
6. You can also use the following endpoints(besides books, takes you there automatically) on the deployed Heroku API linked above. 

## Endpoints

| Description | URL         | Method      | Required Properties for Request | Sample Sucessful Response |
| ----------- | ----------- | ----------- | ------------------------------- | ------------------------- |
| Get All Recipes | `http://localhost:3001/api/v1/foods` | GET | none | array containing all recipe objects |    
| Get Single Recipe | `http://localhost:3001/api/v1/foods/:food_id` <br> *where food_id will be the id number of single recipe* | GET | none | array containing an object of single recipe info |

## Technologies Used

- Express
- JavaScript
- Node
- Heroku
- Postman

## Authors
- [Christine Rowland](https://github.com/Fordo29)
