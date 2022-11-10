[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
  # E-Commerce Back-End
  <br>

  

  ## Description: 
  This application provides the back-end framework for e-commerce applications. 
  &nbsp;
  &nbsp;

  &nbsp;
  &nbsp;
  ## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Questions](#questions)
  <br>

  &nbsp;
  &nbsp;
  ## Installation:
  1. Clone this repository to a local file.

  2. This application runs on node.js. If you don't have it installed, download [Node.js](https://nodejs.org/en/) (version 16.18.0 LTE). It also requires access to the MySQL open-source database. You can download MySQL and create an account [here](https://www.mysql.com/).

  3. Rename the ".env.EXAMPLE" file to ".env" and open it in a code editor or Notepad. Type your MySQL username (the default is "root" if you didn't create one) inside the quotation marks following "DB_USER =", then enter your MySQL password inside the quotation marks following "DB_PASSWORD =".

  3. To install necessary dependencies, open the command line and run the following command:
  >           npm i
  
  
  4. Next, use the command line to login to MySQL (substitute your username for "root" if necessary):

  >           mysql -u root -p

  5. Enter your MySQL password when prompted. Then run the following commands, one at a time, to create your database:
  <br>
  >          DROP DATABASE IF EXISTS ecommerce_db;

 <br>   

  >          CREATE DATABASE ecommerce_db;

  6. Finally, enter the following command to exit the MySQL Shell:

  >          quit


  &nbsp;
  &nbsp;
  ## Usage:
  1. This program provides sample data and table models that can be edited to adapt to your specific needs. The relevent files are located in the "models", "routes/api", and "seeds" folders. Please refer to [Sequelize Docs](https://sequelize.org/docs/v6/) for guidance on syntax construction.
  2. Once you have entered your data in the "seeds" folder, run the following in the command line to populate your database:

  >          npm run seed

  3. Your back-end server is now ready for use! Run the following command to spin it up:

  >          npm start
  &nbsp;
  &nbsp;

  &nbsp;
  &nbsp;
  ## License:
      This project is licensed under the MIT license.

    
  &nbsp;
  &nbsp;

  ## Contributing:
  If you would like to contribute to this project, please use a fork to push your code to the repo and make a pull request.
  &nbsp;
  &nbsp;


  &nbsp;
  &nbsp;
  ## Questions:
  If you have questions about this project, please contact me at [jkanvision@knights.ucf.edu](mailto:jkanvision@knights.ucf.edu). You can view my other projects by visiting my GitHub profile: [https://github.com/jkanvision](https://github.com/jkanvision).