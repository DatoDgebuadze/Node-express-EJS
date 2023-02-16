# This project is focused on working with EJS, a template engine used to render HTML code using Node.js. The project uses Express.js, a popular framework for building web applications with Node.js.

## Installation
### Before starting, make sure to have Node.js and npm installed on your system. To install EJS, open your terminal and type the following command:


## npm install ejs
### This will install EJS in your project.

## After installing EJS, you also need to install Express.js. To do so, type the following command:

### npm install express
## Running the project
### To run the project, type the following command in your terminal:

### node app.js
# Usage
### The project contains two main routes:

### The root route ("/")
### The weather route ("/weather")
## Root Route
### The root route returns a simple message. To access it, open your browser and type "localhost:3000" in the address bar.

## Weather Route
### he weather route has two ways to access it:

### By using query parameters: type "localhost:3000/weather?day=<day>" in the address bar, where <day> is the day of the week you want to get the weather for. If you don't provide a day, a welcome message will be displayed.


### By using route parameters: type "localhost:3000/weather/<day>" in the address bar, where <day> is the day of the week you want to get the weather for. If you don't provide a day, a welcome message will be displayed.
When accessing the weather route with a valid day, the project will render an HTML template using EJS, which displays the weather information for the selected day.

# Technologies used
## The project uses the following technologies:

# EJS
# Node.js
# Express.js

### Author: Davit Dgebuadze
