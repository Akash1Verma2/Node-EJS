# Node EJS Backend Practice

This repository contains my backend development practice while learning Node.js and Express.js.  
It includes routing, EJS templating, static files, and dynamic rendering using JSON data.

## Technologies Used
- Node.js
- Express.js
- EJS
- HTML
- CSS
- JavaScript

## Features
- Express server setup
- Dynamic routes using route parameters
- Rendering pages using EJS templates
- Using partials (head and footer)
- Serving static files from the public folder
- Displaying dynamic data from a JSON file
- Simple Instagram-like profile page
- Dice roll generator page

## Project Structure
Node-EJS
│
├── public
│   ├── css
│   │   └── style.css
│   └── js
│       └── app.js
│
├── views
│   ├── includes
│   │   ├── head.ejs
│   │   └── footer.ejs
│   ├── instagram.ejs
│   ├── home.ejs
│   └── rolldice.ejs
│
├── data.json
├── index.js
└── package.json

## How to Run the Project

1. Clone the repository
2. Install dependencies
npm install
3. Start the server
node index.js
4. Open in browser
http://localhost:3000

## Learning Purpose
This project was built as part of my backend learning journey to understand how Express.js works with EJS templates and dynamic data rendering.