# Ecommerce backend example
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#license)
  ## Description
  This project demonstrates the use of node.js, express, mysql, dotenv, and sequelize to build a backend server for an ecommerce website. The server provides RESTful APIs that can be interacted with using tools like Insomnia. For a detailed explanation of the project, please refer to the provided video demonstration link.
  ## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contribution](#contribution)
  - [Tests](#tests)
  - [License](#license)
  ## Installation
  refer to usage information or for a video demonstration refer to the video below.

  Demonstration Video:
  https://drive.google.com/file/d/1HesdD2rST-S5xZgaB87J-LMFOLlGssdl/view

  ## Usage
  To use the app you must have node.js and mysql installed on your system. For development I used node.js version 20. Clone the repository to your machine. Open a terminal inside the repository and run the command 'npm install' to install all dependencies. Then you must login to mysql through your terminal by running 'mysql -u root -p' and enter your password for mysql when prompt. Once logged in run 'SOURCE db/schema.sql' to create the database on your machine. Close mysql and open a new terminal. Run 'node seeds/index.js' to seed the database with data to get started. The last thing to do before running the server is to create a .env file in the root of the project. There is an example .env file given to you. Inside the .env file add your mysql username and password. Once you have done all of this you can run 'npm start' to start the server. You can now use insomnia to make http requests to the server. The server is running on localhost:3001. Below are the routes you can use to interact with the server. For more information refer to the video demonstration link above.

  - http://localhost:3001/api/products
  - http://localhost:3001/api/products/:id
  - http://localhost:3001/api/categories
  - http://localhost:3001/api/categories/:id
  - http://localhost:3001/api/tags
  - http://localhost:3001/api/tags/:id


  ## Contribution
  For this project I worked with Chase Seaberger. 
  ## Tests
  N/A
  ## License
  https://opensource.org/licenses/MIT
  Copyright <YEAR> <COPYRIGHT HOLDER>
      Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
      The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
      THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
  ## Questions
  For any questions feel free to connect with me on github or by email.
  ### Contact
  GitHub: willber10
  Email: Willberschickler@gmail.com