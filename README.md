# Angular Bridge Course: book-app

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.0.2.

## Quick Note on Project Functionality

This code comes directly from the Angular Bridge Course videos on **Routing** and **API Consumption**. Though those videos only show how to display and create books, this project does finish implementing the delete and update functionality.

## Downloading & Running This Project

1. Make sure to download the necessary node modules by running `npm install`
2. Run app using `ng serve` then navigate to `http://localhost:4200/`

## Setting Up JSON Server

This project will use [json-server](https://www.npmjs.com/package/json-server) to setup a quick API. It already contains a `db.json` file that will act as our dummy database. To setup JSON server for this project, follow these steps:

1. Navigate into this project's folder on your terminal
2. Install the server: `npm i json-server`
3. Start the server: `json-server --watch db.json`
4. If you need to shut the server down: `Ctrl + C`

## Examples & Demos

This project demonstrates how to use the **Angular Router** and using **HttpClient** to consume APIs. This app manages a set of books and allows a user to view, add, delete, and update those books. However, it is assumed that the book data is managed by an API using `json-server` at `localhost:3000`.

