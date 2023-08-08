# CrudOP
This repository contains a simple CRUD (Create, Read, Update, Delete) application built using Axios, a promise-based HTTP client for the browser. The app interacts with a JSON file to perform these CRUD operations. This README will guide you through the process of setting up and using the app.
1. Create react app using npx create-react-app app_name
2. Create json file and store all the data(for this i have created db.json)
3. Then install all the dependencies :
   Install axios react-router-dom bootstrap json-serevr
   Once you installed the dependencies run this command:
   npx json-server --watch db.json
The app provides a user interface for performing CRUD operations on a collection of items. Here's how to use the app:

CRUD App with Axios
This repository contains a simple CRUD (Create, Read, Update, Delete) application built using Axios, a promise-based HTTP client for the browser and Node.js. The app interacts with a JSON file to perform these CRUD operations. This README will guide you through the process of setting up and using the app.

Prerequisites
Before you begin, make sure you have the following installed:

Node.js and npm (Node Package Manager)
Getting Started
Clone this repository to your local machine using:
bash
Copy code
git clone https://github.com/your-username/crud-app-with-axios.git
Navigate to the project directory:
bash
Copy code
cd crud-app-with-axios
Install the required dependencies:
bash
Copy code
npm install
JSON Data
This app uses a JSON file to simulate a data storage mechanism. The data.json file located in the data directory contains the initial data for the application. You can modify this file as needed.

Running the App
To start the app, run the following command:
Copy code
npm start
This command will start a local development server and open the app in your default web browser.

Usage
The app provides a user interface for performing CRUD operations on a collection of items. Here's how to use the app:

> Create
Click on the "Add Item" button.
Fill in the required fields in the form that appears.
Click "Submit" to add the item to the collection.
> Read
The list of existing items will be displayed on the main page.
> Update
Click the "Edit" button next to the item you want to update.
Modify the fields as needed in the form that appears.
Click "Update" to update the item.
> Delete
Click the "Delete" button next to the item you want to remove.
Confirm the deletion when prompted.



