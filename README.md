# BackEndE-Commerce

## Desctiption 
This assignment required us to build the back end for an e-commerce site by modifying the starter code given to us. The application uses a working Express.js API while interacting with a MySQL database using Sequelize. This application is just the back end of the application, meaning that there is no front end or a developed website for the program. The accepted criteria are as follows: 

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

Video Demonstration Link: https://drive.google.com/file/d/1Qgn8pvSfj5bdky1mW_orXE-pmwYYuYyK/view

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions?](#questions?)
* [License](#license)

## Installation
To install this program, make sure to be in your Terminal and be in the right folder to download the applicaiton. Then, run this comand:
```bash
git clone git@github.com:ucruz2025/BackEndE-Commerce.git
```

## Usage
You'll need to install the dependencies first to ensure the application will be running. Run the following command on your terminal within the BackEndE-Commerce folder:
```bash
npm install
```

After installing the dependencies, you can go to the 'db' folder and copy/paste the schema.sql code onto your MySQL workbranch to create the database. Once created, go back to your terminal and seed the data to your database:
```bash
npm run seed
```

Once you see on your console that the data has been seeded, you can start the program. To start using the program, just run the following command in your terminal and the program will be active:
```bash
npm start
```

On any browswer type 'localhost:3000' and you'll be redirected to the application. The page will prompt a heading saying that you're on the "Wrong route!". To properly access your seeded data, go to your routes folder and type in the proper url extensions to access either the categories, products, or tags of the companies transaction. 

## Contributing
Contribution details can be found under the license section of this file.

## Tests
There are no tests for this application.

## Questions?
If you happen to have any further questions regarding the project, feel free to reach out to:

Github: ucruz2025
Email: ucruz2025@gmail

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
Copyright 2021 Uriel Cruz Salgado

  Permission is hereby granted, free of charge, to any person obtaining a copy 
  of this software and associated documentation files (the "Software"), to deal 
  in the Software without restriction, including without limitation the rights 
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell 
  copies of the Software, and to permit persons to whom the Software is furnished 
  to do so, subject to the following conditions:

  Contact owner of this software. Information can be found under "Questions?" section.
      
  The above copyright notice and this permission notice shall be included in 
  all copies or substantial portions of the Software.
      
  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, 
  EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, 
  WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN 
  CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
      
  Live link to license: https://opensource.org/licenses/MIT
